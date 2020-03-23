# Budget-Tracker

## Description

An online/offline Progressive Web App that tracks account balance, withdrawals, and deposits. It can be downloaded and used online or offline due to the inclusion of an app manifest and service worker. Data entered in offline mode is stored client-side in IndexedDB, then stored server-side in MongoDB once online again. The app also uses compression to optimize performance.

| Technologies used:                                                                         |
| ------------------------------------------------------------------------------------------ |
| Node.js, Express, MongoDB, Mongoose, IndexedDB, JavaScript, Chart.js, HTML, CSS, Bootstrap |

## Demo

![Budget Tracker Demo](/public/budget-tracker.gif)

## Installation

Open the root directory in terminal and enter:

```sh
npm install
```

```sh
npm start
```

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## License

© 2020 Zachary Sadovszky

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.