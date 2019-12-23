### Install Dependencies

- npm i express express-validator bcryptjs config gravatar jsonwebtoken mongoose request
- npm i -D nodemon concurrently

### Init client folder

- npx create-react-app client
- npm i axios react-router-dom redux react-redux redux-thunk redux-devtools-extension moment react-moment

### Install heroku cli

- heroku login
- use postscript to build on the heroku (in server package.json)
- heroku create (create heroku app)
- heroku git:remote -a dry-bayou-76370 (add remote repo)
- git push heroku master

### Create production build to heroku

- cd client && npm run build
