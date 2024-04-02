# Group 37 Weather App for Winegrowers

## Set-Up Guide

**0. Before doing any of this, if you're using your own laptop/desktop, make sure you've got the latest versions of node and npm installed (npm v: 4.0.5 & node v: 7.4.0) :**

```sh
node -v
npm -v
```

## Installation

**1. Install the dependencies :**

```sh
npm install
```

## Development Workflow

**4. Start a live-reload development server :**

```sh
npm run dev
```

> This is a full web server for your project. Any time you make changes within the `src` directory, it will rebuild and even refresh your browser.

**5. Generate a production build in `./build` :**

```sh
npm run build
```

**6. Start local production server with [serve](https://github.com/zeit/serve):**

```sh
npm start
```

> This simply serves up the contents of `./build`. Bear in mind, if you use this, the localhost port your server is running on will refresh, and you'll also need to restart it to see any changes you've made to the code in `src`.

**7. To enable the weather app's location function. Please use localhost:[PORTNUMBER]:**

For exmaple:
The output in your device's powershell is as follows:
Powershell:

---

    Running on http://192.168.0.35:53415 [copied to clipboard]

---

You should type in your web browser: localhost:53415
