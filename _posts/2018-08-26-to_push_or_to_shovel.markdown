---
layout: post
title:      "To Push or to Shovel?"
date:       2018-08-27 00:39:23 +0000
permalink:  to_push_or_to_shovel
---



Welcome back to episode 2 of my delve into the world of coding!

The last month has been a whirlwind of learning my first progreamming language, Ruby.  One thing that seemed to come up  frequently in group discussions regarding arrays was whether to use the push or shovel method to add a vriable to an array. 

As a refresher the "shovel method" uses `<<` to add a **single** element to the end of an array. For example:

```
teenage_muntant_ninja_turtles = ["Leonardo", "Donatello", "Raphael"]
# we forgot the party dude

teenage_muntant_ninja_turtles << "Michelangelo"

#So "<<"   adds Michelangelo to the end of the array and it would looke like 

teenage_muntant_ninja_turtles = ["Leonardo", "Donatello", "Raphael", "Michelangelo"]

```

Using the same Teenage Mutant Ninja Turtles example, we realize that Master Splinter is an intregral par of the TMNT team, but to add two elemets to the initial arry we cant use the `<<` we need to use the `.push` method to add **multiple** elements. 

```
teenage_muntant_ninja_turtles = ["Leonardo", "Donatello", "Raphael"]
teenage_muntant_ninja_turtles.push("Michelangelo, "Splinter")
#=> ["Leonardo", "Donatello", "Raphael", "Michelangelo", "Splinter"]
```

That seems pretty easy right? Shovel adds one variable and `.push` adds multiple elements to an array. Each method has different implications based on the programmerusing them, but I hope that adds some clarification. Cowabunga dude!

[<iframe src="https://giphy.com/embed/cFdHXXm5GhJsc" width="480" height="377" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/tmnt-teenage-mutant-ninja-turtles-cFdHXXm5GhJsc">via GIPHY</a></p>](http://)
