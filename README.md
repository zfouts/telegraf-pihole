# telegraf-pihole
Telegraf Pihole Visualization

Dashboard based loosely on https://github.com/gmmoreira/pihole-stats-telegraf without any external dependancies



## Installation

```
# PiHole monitoring
[[inputs.httpjson]]
  name = "pihole1_stats"
  servers = [
    "http://pihole.example.com/admin/api.php",
  ]
  response_timeout = "5s"
  method = "GET"
```

