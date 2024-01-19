# mqtt2slack.py

```
$ cd ~work/
$ git clone git@github.com:yoggy/mqtt2slack.git
$ cd mqtt2slack
$ cp config.yaml.sample config.yaml
$ vi config.yaml

    mqtt_host: broker.emqx.io
    mqtt_port: 1883
    mqtt_client_id: mqtt2slack0001
    mqtt_use_auth: false
    mqtt_username: username
    mqtt_password: password
    mqtt_subscribe_topic: message/to/slack
    slack_api_url: https://slack.com/api/chat.postMessage
    slack_api_token: xoxb-xxxxxxxxxxxxx-xxxxxxxxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxx
    slack_api_channel: slack_channe

$ ./mqtt2slack.py

```


## Copyright and license

Copyright (c) 2024 yoggy

Released under the [MIT license](LICENSE.txt)
