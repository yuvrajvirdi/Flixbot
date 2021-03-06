# Flixbot

A discord bot for movies, built on Node.js

<img src="/logo/Flixbot-4.png" width="150" height="150"/>

# Introduction

* Flixbot is a discord bot that allows for users to manage their servers as well as allowing the ability to conduct different types of queries on movies.
* The bot utilizes the [OMDB](http://www.omdbapi.com) and [TMDB](https://www.themoviedb.org) APIs to obtain accurate and up to date data on movies.
* Built on NodeJS.

## Commands

* **!kick** *user*: kicks user from the server.
* **!ban** *user*: bans user from the server.
* **!announce** *message*: pings all members and announces a message in the channel.
* **!roleadd** *user*: adds a role to a user.
* **!roleremove** *user*: removes a role from a user.
* **!info** *movie*: gets relevant information on a movie, such as plot, runtime, genres, actors, and more.
* **!rating** *movie*: shows the rating on a movie from accredited sources, as well as a decision-tree based conclusion on if the movie is good.
* **!somethinglike** *movie*: recommends one of the top 3 movies similar to the queried movie, and also gives an overview on it.
* **!trending**: gets the top 5 trending movies
* **!watch** *movie*: creates a link for where to watch the queried movie. (coming soon)
* **!ping**: checks if Flixbot is active and gets the latency at which it's operating.

# Dependencies

* [NodeJS](https://nodejs.org/en/)
* [Axios](https://axios-http.com/docs/intro)
* [Discord.js](https://discord.js.org/#/)
