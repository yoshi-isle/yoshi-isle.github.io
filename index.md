---
layout: default
title: Blog
---

# Blog

Welcome to my blog!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>
