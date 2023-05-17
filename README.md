# Astronomy-Bot
This Astronomy Bot was developed using Python programming language and leverages the APOD API for accessing the Astronomy Picture of the Day archive. The bot is designed to run as a background process, continuously fetching images from the API and posting them at regular intervals.
The bot uses libraries such as discord, aiohttp, asyncio, datetime, and pandas to enable the required functionality.
The bot defines functions to retrieve APOD data for a specific date, send APOD images as Discord embeds, and fetch APOD images within a given date range.
The bot fetches APOD images by making asynchronous API requests using the aiohttp library. It retrieves the image data, creates a Discord embed with the image and relevant information, and sends it to a specified channel.
The bot loops through a specified date range using pandas. For each date, it sends the APOD image and waits for 3 minutes before proceeding to the next date.The bot initializes a discord.Client object, sets up event handlers, and runs the bot using the client.run() method.



