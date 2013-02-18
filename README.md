canitweet
=========

This is a mostly pointless script that determines if some bit of text would
fit in a tweet.

```shell
$ canitweet "this? of course, it's clearly less than 140 characters"
Tweet away! (86 characters remaining)

$ canitweet "The White-bellied Sea Eagle is a large diurnal bird of prey in the family Accipitridae. A distinctive bird, adults have a white head, breast, under-wing coverts and tail."
Shucks, that's 30 characters too long.
```

If no argument is supplied, the clipboard is checked if possible.


```shell
$ canitweet
No argument supplied, using clipboard:

    http://en.wikipedia.org/wiki/Malbolge

Tweet away! (103 characters remaining)
```
