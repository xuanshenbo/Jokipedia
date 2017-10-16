# Jokipedia

Jokipedia is a Hipchat add on. It's a robot that tells _appropriate_ 
workplace jokes.

In a Hipchat room with Jokipedia installed, Dave can type:
> Dave: /joki

Then Joki will tell a random _appropriate_ workplace joke like:
> Jokipedia: I met the Godfather of the Scottish mafia earlier... 
He made me an offer I couldn’t understand.


Next steps:

* Productionisation
* `/joki` command takes an argument, to search matching jokes. 
For example, `/joki UDP` will get a joke like
> Jokipedia: I would tell you a joke about UDP, but you probably 
wouldn't get it.
* Fixed-time joke pushing. For example, Joki would 
push a joke to a Hipchat room to entertain people at the beginning of 
every day
