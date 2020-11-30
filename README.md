# pub-sub-express-nodejs
A small test implementation for pub-sub with GCP

## Packages installed

express — A lightweight Node.js web framework for spinning up RESTful APIs. We will use this to handle routing in our backend API
nodemon — This package will help us automatically restart our development server when we make code changes/edits
body-parser — A middleware to parse incoming request inputs into our req.body object
morgan — HTTP request logger middleware for Node.js. This will help us debug our API while in development
helmet — This is a collection of middlewares for which our express-based server by setting HTTP headers which conforms to best security practices
cors — This package will help enable cross-origin resource sharing on our server
dotenv — This package will enable us to have access to the environment defined in a .env file from our Node application via the process.env object
google-cloud/pubsub — This is the Node.js client for Cloud Pub/Sub. We will be using this to publish messages and subscribe to topics defined in our pub/sub console