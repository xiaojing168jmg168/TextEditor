
## (PWA) : Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description



## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

## Installation



*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure
``````
*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*

![alt text](/assets/images/jate-1.png)


2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````
*Below is the screenshot of the running at npm run start and npm run build* 

![alt text](/assets/images/jate-2.png)

*Below is the screenshot of the generated HTML, service worker and a manifest file*

![alt text](/assets/images/jate-3.png)

3.
``````
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
``````
*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](/assets/images/jate-4.png)

4.
``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
*Below is the  screenshot of content in the text editor has been retrieved from the IndexedDB"*

![alt text](/assets/images/jate-10.png)

5.
``````
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
``````
*Below is the screenshot of icon on the desktop"*

![alt text](/assets/images/jate-6.png)

6.
``````
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
``````
*Below is the screenshot of the static assets pre cached upon loading with subsequent pages and static assets"*

![alt text](/assets/images/jate-7.png)

![alt text](/assets/images/jate-9.png)

7.
*The following image shows the application's ```manifest.json``` file:
![alt text](/assets/images/jate-8.png)

8.

 ````````
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
````````
![alt text](/assets/images/jate-5.png)



 
## License

This project is licensed under the terms of the MIT license.