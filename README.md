# TagService 
a nice a simple way to put different valuetypes where you want them

Should be used with Roblox Studio, and placed inside a ModuleScript. Preferably in ServerScriptService

This module is mostly useful as ~~good practice for me to use github for my stuff more~~ a nice module that can cheaply and reliably return object-held variables without having to type them out all the time


# Functions
The module currently only has one method.

# TempTag

Arguments, in order:   
`valuetype` type of roblox Value object (StringValue, etc)   
`where`  where to put it                                              
`name`  name the object  
`value`  value of the object  

```
TagService = require(game.ServerScriptService.TagService)
tag = TagService:TempTag(valuetype, where, name, value)
```

TempTag will return a `tag` object, which can be used in the same way any other Roblox Value object can be used



