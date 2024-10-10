# IHadThe Backend API

This repository contains the backend code for the _IHadThe_ app, developed using **JavaScript/TypeScript**. The backend handles user authentication, meal reviews, and data storage.

## Features and Included Libraries

-   **ExpressJS**: A fast and minimalist web framework for Node.js, used to build robust and scalable APIs.
-   **Mongoose**: A MongoDB client that provides an elegant way to interact with MongoDB databases and define data schemas.
-   **axios**: A library for making HTTP requests, simplifying the process of fetching data from external sources or APIs.
-   **bcrypt**: Used for encrypting and decrypting sensitive data, such as passwords and tokens, enhancing application security.
-   **cors**: Handles Cross-Origin Resource Sharing, allowing the API to be accessed by clients from different domains.
-   **helmet**: Secures Express apps by setting various HTTP headers to protect against common web vulnerabilities.
-   **morgan**: A logging tool for HTTP requests, aiding in debugging and monitoring the application.
-   **http-errors**: Simplifies the creation of HTTP error responses, improving error handling.
-   **nodemon**: Monitors for changes in code and automatically restarts the server during development.
-   **ts-node**: Executes TypeScript files directly, facilitating the writing and running of TypeScript code without transpiling.
-   **TypeScript**: A strongly typed superset of JavaScript that enhances code quality and provides better tooling.
-   **ESLint**: Enforces code style and maintainability rules, ensuring code follows best practices and stays consistent.

## Requirements

Make sure you have the following software installed on your system:

-   [Node.js](https://nodejs.org/) - JavaScript runtime environment
-   [npm](https://www.npmjs.com/) - Package managers for Node.js
-   [MongoDB CLI](https://docs.mongodb.com/manual/installation/) (optional) - If you want to connect to a MongoDB database on your local system.

## Usage

Follow these steps to get started with this starter kit:

1. Clone the project to your local machine:

    ```shell
    git clone git@github.com:wpendl99/IHadThe-Backend-API.git
    ```

2. Navigate to the project directory:

    ```shell
    cd IHadThe-Backend-API
    ```

3. Install the required dependencies using either Yarn or npm:

    ```shell
    npm install
    ```

4. Create a copy of the `.env.example` file and name it `.env`:

    ```shell
    cp .env.example .env
    ```

5. Configure the environment variables in the `.env` file according to your project's requirements. This file stores sensitive information like database credentials and API keys, so make sure to keep it secure.

6. Start the development server:

    ```shell
    npm run dev
    ```
