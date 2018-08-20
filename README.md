## Overview

Webpack backend example


## Running locally for development

#### Setup your environment

* [Install **npm**](https://www.npmjs.com/get-npm) and [Install **Yarn**](https://yarnpkg.com/en/docs/install#debian-stable)(Optional)

Install Docker (Optional):

* [Install **Docker**](https://docs.docker.com/install/#supported-platforms)
* [Install **Docker compose**](https://docs.docker.com/compose/install/)



#### Run project without docker

```
# Generate bundle using webpack development mode
yarn build:dev

# Run webpack dev watch for locally development
yarn build:dev:watch

# Generate bundle using webpack production mode
yarn build:prod
```

#### Run project with docker (The easy way)

```
# Generate bundle using webpack development mode
yarn docker:build:dev

# Run webpack dev watch for locally development
yarn docker:build:dev:watch

# Generate bundle using webpack production mode
yarn docker:build:prod
```

#### **Warning:** Problems with `node_modules` packages?

Try cleaning the `node_modules` if you have tried to install the packages without docker, and you have tried to use them later.
```
yarn build:clean
```


## Acknowledgements

This code is compiled using webpack 4.