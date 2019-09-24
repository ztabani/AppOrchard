
Testing Epic App

![Screenshot with Sample Data](/Screenshot.png)

## Running the app from Epic App Orchard

1. Clone the repository
2. Install the needed modules (assumes you already have yarn installed): `yarn install`
3. Add your app credentials to `credentials.js`
4. Run using yarn: `yarn start`.  If you need to run HTTPS then use the `start-https` task which depends on `sudo` and will require your administrator password: `yarn start-https`.  You can now browse the sample data at [http://localhost:3000](http://localhost:3000) or continue to the next step.
5. Launch from [Epic App Orchard Simulator](https://apporchard.epic.com).  The launch URL will be `https://YOUR_HOST_NAME/fhir/epic/launch`

