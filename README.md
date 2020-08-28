# Whitelist
Simple whitelist plugin for Bukkit. It uses names instead of UUIDs, because of some bugs on offline-mode servers. You can also change whitelist kick message without restarting your server.
## Download
See [Releases](https://github.com/xishift/Whitelist/releases)
## Usage
Permission for commands: **whitelist.use**  
Permission for notifications: **whitelist.notifications**  
Command usage: **/whitelist <on/off/add/remove/list/message>**
## Configuration
```yaml
messages:
  usage: " &8» &cUsage: &6/whitelist <on/off/add/remove/message/list>"
  list: " &8» &cWhitelisted players: &6%s"
  toggle-on: " &8» &7Whitelist has been &aenabled."
  toggle-off: " &8» &7Whitelist has been &cdisabled."
  player-added: " &8» &7Player &6%s &7has been &aadded &7to the whitelist."
  player-removed: " &8» &7Player &6%s &7has been &cremoved &7from the whitelist."
  player-not-provided: " &8» &cYou need to provide player name."
  message-not-provided: " &8» &cYou need to provide a message."
  player-not-found: " &8» &cThis player is not whitelisted!"
  message-set: " &8» &7Whitelist message set to: &r%s"

notifications:
  enabled: true
  message: " &8» &cPlayer &6%s &ctried to join but is not whitelisted!"```
