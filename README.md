# slack-notify

Incomming webhookでslackに飛ばすときに使うコマンド。

# INSTALL

```
$ brew tap ymmtr6/slack-notify
$ brew install slack-notify
```

# SETUP

1. setting Incomming webhook in Slack (and get url).
2. url set env *SLACK_WEBHOOK*. 


# USAGE
```
$ df -h | slack-notify
```
or
```
$ slack-notify "this is message from commands."
```
