# Node.js Cache Web Starter Overview

The Node.js Cache Web Starter demonstrates how to use the Bluemix Data Cache service. The app lets the user enter key-value pairs to cache, then lookup or delete keys and change existing cached values.

If deploying to Bluemix, note that the Data Cache service does not have a free plan. The "Shared" plan is used instead.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy)

## Run the app locally

This app will run locally using an in-memory cache instead of the Data Cache service if the VCAP_SERVICES environment variable is not set.

1. [Install Node.js][]
2. Download and extract the starter code from the Bluemix UI
3. cd into the app directory
4. Run `npm install` to install the app's dependencies
5. Run `npm start` to start the app
6. Access the running app in a browser at http://localhost:3000

[Install Node.js]: https://nodejs.org/en/download/
