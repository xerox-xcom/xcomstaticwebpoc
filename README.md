POC to test viability of deploying static xerox.com content through an Azure Static Web Service

- Static content is under src/ folder. Folder serves as the root web server content folder ("/")
- If a change is made and pushed to master, the CICD workflow (Github Action) will trigger and publish the content to the site
- We will want to decide whether to inject a PR-based process into this flow
- Static Web App is deployed in Azure under he XCOM POC subscription. It is called "xcomstaticwebpoc"
- Content viewable at: https://thankful-sand-015e6fd0f.5.azurestaticapps.net/. Note the index.html does an auto-redirect to www.xerox.com.
- Sample URL to see an asset on the site: https://thankful-sand-015e6fd0f.5.azurestaticapps.net/sidebar_image.jpg
