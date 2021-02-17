

## NPM
Install https://www.npmjs.com/get-npm

## IDE
Download visual studio code and install it: https://code.visualstudio.com/

# Install botkit

## Install botkit

Taken from here https://www.botkit.ai/docs/v4/

npm install -g yo generator-botkit
yo botkit

(Not sure if needed: npm install --save botbuilder-adapter-webex. I think the generator creates it already)

You can now open the folder with your installed IDE

# Register you bot

https://developer.webex.com/docs/bots 
Note down the token when you create the bot

# MAke your bot available

Register on https://ngrok.com/ and Download the tool

# Adapt you bot

## Start ng rok 

Your service runs usually on 3000 start ngrok via 
ngrok http 3000

## Start you app

NG rok will give ypu a public address on the fly. Use this address and adapt 

PUBLIC_ADDRESS=https://56576456564e.ngrok.io
and
TOKEN to the token from the generated bot


start you bot via npm start & search for your bot
challenge.txt
challenge.txt wird angezeigt.
