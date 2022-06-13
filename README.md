# 3-Column-Card
 
## Welcome! 
Thanks for checking out my code.

## The challenge

The challenge is to build out 3 column card and get it looking as close to the design as possible.

## My process
- I structured all the HTML 
- I used CSS custom properties to style
- I used the Flexbox to locate each element where it should be
- I returned to the HTML and made some changes to make it as clean as possible


### What I learned
In this challenge I increased my skills using HTML tags to separete it in blocks, for exemple: 

```<div class="container">
    <div class="sedans">
      <img src="icon-sedans.svg" alt="">
      <h2>SEDANS</h2>
        <p>
         Choose a sedan for its<br> affordability and excellent<br> fuel economy. Ideal for<br> cruising in the city or on<br> your next road trip.
        </p>
      <button>Learn More</button>
    </div>
  ```


I'm really proud of this part of the CSS where I changed button background using the sedans button selector without having to create a specific class for buttons:
```
.sedans {
	background-color: hsl(31, 77%, 52%);
	display: flex;
	width: 300px;
	flex-direction: column;
	align-content: center;
	justify-content: center;
	border-top-left-radius: 5px;
	border-bottom-left-radius: 5px;
}	

.sedans button {
	color: hsl(31, 77%, 52%);
}
 ```

### Useful resources

- [flexbox] (https://flexboxfroggy.com/)
This is an amazing site which helped me finally understand how flexbox works.

## Author
- Linkedin - Welton Torres (https://www.linkedin.com/in/welton-torres-34363024/)
- Frontend Mentor - [@weltontorres](https://www.frontendmentor.io/profile/weltontorres)
- Twitter - [@weltontorres](https://twitter.com/weltontorres)

