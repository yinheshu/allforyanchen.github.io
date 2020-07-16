---
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<ul>
  {% if post.title contains '【' %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endif %}
</ul>
