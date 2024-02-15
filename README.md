# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge 

Your challenge is to build out this recipe page and get it looking as close to the design as possible.

This was an overall easy challenge, I had to google some answers

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

 - I started with the html file and moved on to the CSS.
 - As I was writing CSS I discovered some flaws in my html.
 - Afterall I made sure it was responsive and that was it.
 - The overall challenge took about 5 hours to complete.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

In this challenge I learned how to style the bullet of a list item using the marker pseudo selector.

```CSS

  li::marker {
    color: white;
  }

```

And I've learned to center the bullet vertically with the text inside the list item like this:

```html
<li><span>Some text</span></li>
```
```CSS
li span {
    display: inline-block;
    vertical-align: middle;
}
```

### Continued development

I want to continue focusing on layout and Typography as I found myself struggling a bit with them.

### Useful resources

- [How to center a bullet](https://idkshite.com/posts/vertical-center-bullet) - This helped me with centering the bullets with the according text. I really liked this solution and will use it going forward.


## Author

- Frontend Mentor - [@zeinghra](https://www.frontendmentor.io/profile/zeinghra)
- Twitter - [@Zein_ghra](https://twitter.com/Zein_ghra)
