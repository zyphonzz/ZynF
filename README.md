!!    ZynF is made for Zerion Premium. This doesnt work with atlantis, it should work with wave, it wont work with solara, it wont work with xeno.   !!

![image](https://github.com/user-attachments/assets/3f441056-0b97-42d6-9cb6-82a5a8a53232)


```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/zyphonzz/ZynF/refs/heads/main/source.luau"))()
```



ZynF adds the following functions to Zerion:



----- dev -----



```
getplayerinfo()
runscriptfromurl()
printidentity()   --   slightly increases real identity ( 3 to 5.1 )
```



--- scripts ---



```
scripthub   --   table filled with scripts
scripthub.infinite_yield
scripthub.dex
scripthub.patchma   --   currentlly being fixed
scripthub.nameless_admin
scripthub.frontlines   --   silent aim + esp + hitbox expander for frontlines
```

you can call these scripts using

```
runscriptfromurl(scripthub.yourscripthere)
```

or

```
scriptnamehere()   --   not suggested for custom scripts, because you will have to add a custom function to _G and to the global environment using getgenv()
```



--- 
