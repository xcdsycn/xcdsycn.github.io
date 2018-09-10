---
layout: page
title: About
permalink: /about/
---
这是最初版本的网站，出于学习的目的。
以后会越来越好的...

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}

