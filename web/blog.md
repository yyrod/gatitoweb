---
layout: default
title: Blog
marquee: See whats happening!!
---

## Blog:

Here you can read the Gatito Linux blog! It's currently a WIP, but I (yyrod) think i can finish it quickly. The posts are sorted by most to least recent.

{% for post in site.posts %}
 <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
{% endfor %}







