+++
title = "Sqwiggle"
description = "Send build status notifications via Sqwiggle"
user = "drone-plugins"
repo = "drone-sqwiggle"
image = "plugins/drone-sqwiggle"
tags = ["sqwiggle"]
categories = "notify"
draft = false
date = 2015-12-15T06:53:13Z
menu = ""
weight = 1

+++

Use this plugin for sending build status notifications via Sqwiggle. You can
override the default configuration with the following parameters:

* `` -

## Example

The following is a sample configuration in your .drone.yml file:

```yaml
notify:
  sqwiggle:
```
