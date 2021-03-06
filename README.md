# Intercom.io Screener - Events
## Demo
[http://yarunluon.github.io/intercom/event/](http://yarunluon.github.io/intercom/event/)

## Challenge
Design and build an interface to display events, given information as structured below. Any solution is valid – e.g. a javascript calendar widget, a beautifully formatted web page, a command line tool.
```javascript
{
"events": [
  {
    "occasion": "Birthday party",
    "invited_count": 120,
    "year": 2015,
    "month": 3,
    "day": 14
  },
  {
    "occasion": "Technical discussion",
    "invited_count": 23,
    "year": 2015,
    "month": 4,
    "day": 24
  },
  {
    "occasion": "Press release",
    "invited_count": 64,
    "year": 2015,
    "month": 6,
    "day": 7,
    "cancelled": true
  },
  {
    "occasion": "New year party",
    "invited_count": 55,
    "year": 2016,
    "month": 1,
    "day": 1
  }
]
}
```

## Approach
I wanted to use the data to tell a story. By having the user participate in the flow, it becomes rewarding to see the information displayed to the user.

## Installation
#### Install Connect Server
Installs a light weight server to serve static pages. Requires [Node](https://nodejs.org/en/).
```sh
$ npm install
```

#### Start server
```sh
# http://localhost:8080
$ node server.js
```
