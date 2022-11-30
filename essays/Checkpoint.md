---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
date: 2022-11-29
published: true
labels:
  - Software Engineering
  - Learning
  - Assignment3
---

**Show what each page will look like. The pages do not have to be “functional” but the design should clear.**
click [here](https://youtu.be/YmE0wsb0mjo)to short screencast of Assignment 3 design


**Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.**

On the top of every pages, I created navbar that allows users to click shopping cart icon. By clicking the icon, it will redirect to the separate shopping cart page to view what’s in the shopping cart and estimated total price. My plan is to add features to edit or/and delete items that the user selected. 


**Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.**

Sessions will be utilized to manage my shopping cart. I will use it as the method to store quantity data so that users can view item in their cart when they returns. I will user arrays in JSON to store within sessions. Format that I will be using for sessions will look like this: {  “Harry Potter” : [0 , 0 ,1],  “Crazy Rich Asian”:[0 ,1, 0] }

**How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**

I will avoid access to my application when the user has not logged in or registered by utilizing session ID cookies to store that a user is logged in and to maintain product data. If the user doesn’t have cookies without logging in, the user will still have access to shopping cart but before redirecting to invoice, the user will be asked to log in or register before accessing to invoice. A security concern with this is that everytime I make changes to server, it will lose stored sessions information.  

**Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**

Upon a successful login, the user’s name will be displayed on the header of pages. I will implement show message such as “(username) logged in” or I will insert new user icons as they successfully logged in. On the complete page, I will display user name and email address to show confirmation, “Thank you (username) for the ordering! Confirmation will be sent to (email address)” 

**If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?**

No, I am not working with a partner. 

**How are you approaching Assignment 3 differently than Assignment 2?**
Compared to Assignment 2, I am taking more time to build design and system. From the instructions, it can tall that there are several ways to build what the assignment is asking for. I’m looking for the ways that I can create in the most efficient and simple way as possible. 
