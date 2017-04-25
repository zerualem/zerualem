## Welcome to my Github page!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ _posts/2017-04-25-PCA.md }}">{{ Principal component analysis }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

