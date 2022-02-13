# ThdhrCal
Mostly designed for private use, but other Home Depot employees may find it useful as well.

## Purpose
This script will check [Kronos](www.mythdhr.com) every so often, and import the work schedule to a Google Calendar. Useful for part-time associates and those with inconsistent schedules.

## Variables
Make a [.env](https://www.npmjs.com/package/dotenv) file to configure your login info:
- HD_STORE_NUMBER
- HD_USERNAME
- HD_PASSWORD

## Google API
Google API info goes in a file named "credentials.json" - see [Google Workspace](https://developers.google.com/workspace/guides/create-credentials) for more info. After user consent, the client key will be saved in "token.json" for future use. Authentication with Google can be a little tricky, so [here's](https://developers.google.com/identity/protocols/oauth2) a guide for those who need it.

Required scopes:
*TBD*
