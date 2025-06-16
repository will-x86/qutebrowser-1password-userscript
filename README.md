# qutebrowser-1password-userscript

Fixed version of the qutebrowser 1password script

I've only tested on a few sites, I'm new to qutebrowser but 1Password is a must for me

Read the code before you run

Thanks !

# **I have the integration with 1Password cli app _on_ **

Ensure you have awk, jq, "op" ( 1Password cli ), sed,rofi


Also, unsure how the original script worked, but I have this key binding for when I'm adding passwords:
```
    keyBindings = {
      normal = {
        ",p" = "spawn --userscript 1password.js";
      };

```

PR's are welcome 

