# angular-auto-deploy

This is a sample angular app to demonstrate and check GitHub workflows to deploy the app using GitHub pages inspired from [this repo](https://github.com/kazuma-0/vue-auto-deploy). 

The main point to note is that while building an angular app the site URL which it is going to be deployed on must be mentioned using the `base-href` flag. Hence, a custom script is added in `package.json` called `prod:build` which is the one called in `deploy.yml`.

## Development server
To run this project locally, have `npm` and `angular-cli` installed globally and then,
- Clone the repo 
- Run `npm install` 
- Run `ng serve` for a dev server
- Navigate to `http://localhost:4200/` 

The app will automatically reload if you change any of the source files.

For further help on the Angular CLI visit their site [here](https://angular.io/cli).