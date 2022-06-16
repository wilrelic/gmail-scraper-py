Yo man,

 -- You will need to set up a project in Google Cloud and activate the Gmail API.
 -- You then need to create new oAuth credentials for a Desktop App to generate client ID etc.
 -- You can now download the json of these credentials and then replace the credentials.json file in this directory.
 -- When you first run the script it will ask you to authenticate, once you have the token it won't ask again.

Basically it is just a simple scraper I have pinched from someone.
I need to pull a bunch of email addresses out of my inbox (over 9000 >.<) for marketing purposes.
The script should basically pull all the messages that contain the query passed in the search_messages() function.
First it pulls the message ID's then it runs a function to parse the parts.
It should then create a folder and save them into it.

It authenticates but doesn't seem to run anything else or return/print anything.
I'm not sure if I'm missing something totally obvious?
I'm used to debugging javascript in real time in a console using logs but have literally zero experience with PY.

PlZ hAlP mE!1!! >.<