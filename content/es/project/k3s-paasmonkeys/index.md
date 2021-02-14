---
title: k3s-paasmonkeys
summary: Mi propio clúster de Raspberry Pi usando K3s
tags:
- Kubernetes
date: "2021-01-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
 caption: ""
 focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/ymedlop
url_code: "https://github.com/ymedlop/k3s-paasmonkeys"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Este es un proyecto personal para configurar un clúster RPi con Kubernetes. Proporcionandome una nube privada para uso educativo.

## Why k3s
[K3S](https://k3s.io/) es una distribución de Kubernetes certificada y de alta disponibilidad diseñada para cargas de trabajo de producción en ubicaciones remotas desatendidas, con recursos limitados o dentro de dispositivos de IoT. Tanto ARM64 como ARMv7 son arquitecturas compatibles.

## Prerequisites
<img align="right" width="100" height="100" src="https://github.com/ymedlop/k3s-paasmonkeys/raw/master/images/cluster-draft.jpg">

* 6 SD card 32GB like [SanDisk 32GB ULTRA microSDHC Card Class 10](https://www.amazon.com/gp/product/B007JTKLEK/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B007JTKLEK&linkCode=as2&tag=alexellisuk-20&linkId=72069d86b6c70e1dc49c2f0ce35f08ef)
* 6 RPi 3b+ (1 Masters and 5 Worker)
* 8-port Ethernet Gigabit Switch like [Netgear GS308](https://www.amazon.de/dp/B07PTTX7MX?aaxitk=SnYYIyTPS3nEg.V.FMD-ig&pd_rd_i=B07PTMXBDK&pf_rd_p=5e2a70c8-77de-4865-9918-07306318c381&hsa_cr_id=8283596160702&sb-ci-n=asinImage&sb-ci-v=https%3A%2F%2Fimages-na.ssl-images-amazon.com%2Fimages%2FI%2F41f7FBBmqpL.jpg&sb-ci-a=B07PTMXBDK&th=1)
* 8-way USB Power-supply
* 6 Cables ethernet
* 6 Cables micro-usb
* RPi 3B+,4B Cluster case like [8 Slot Cluster Cloud](https://www.ebay.de/itm/8-Slot-Cluster-Cloud-For-Raspberry-Pi-4B-3B-and-other-single-board-computers/123315692330?hash=item1cb630232a:m:mgb2CCUuG3V2u1RKG3BDyGg&var=423715705189)

[Aquí](https://github.com/ymedlop/k3s-paasmonkeys/blob/master/README.md) puedes leer más sobre ello.