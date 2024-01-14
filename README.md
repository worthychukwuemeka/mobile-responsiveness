# Mobile Responsiveness Cheatsheet

## Introduction

Welcome to this cheatsheet on how to make your website mobile-responsive using CSS media queries. Ensuring your website looks great on various devices is crucial for a positive user experience. Let's get started!

## CSS Media Queries

CSS media queries allow you to apply specific styles based on the characteristics of the user's device. Here's how to use them:

```css
/* Default Styles */
body {
    font-size: 16px; /* Default font size */
    /* Add your other default styles here */
}

/* Media Query for Small Screens (Mobile Phones) */
@media only screen and (max-width: 600px) {
    body {
        font-size: 14px; /* Adjust font size for smaller screens */
        /* Add styles specific to small screens here */
    }
}

/* Media Query for Medium Screens (Tablets) */
@media only screen and (min-width: 601px) and (max-width: 1024px) {
    body {
        /* Add styles specific to medium screens here */
    }
}

/* Media Query for Large Screens (Desktops) */
@media only screen and (min-width: 1025px) {
    body {
        /* Add styles specific to large screens here */
    }
}
```

## Explanation

1. **Default Styles:** Set the default styles for your website.

2. **Small Screens (Mobile Phones):** Adjust styles for screens with a maximum width of 600 pixels.

3. **Medium Screens (Tablets):** Add styles for screens with widths between 601 and 1024 pixels.

4. **Large Screens (Desktops):** Apply styles for screens with a minimum width of 1025 pixels.

## Tips for Mobile Responsiveness

- **Flexible Layouts:** Use relative units like percentages and avoid fixed widths to allow content to adapt to different screen sizes.

- **Fluid Images:** Set the maximum width of images to 100% to ensure they scale proportionally on smaller screens.

- **Responsive Typography:** Use `em` or `rem` units for font sizes to maintain readability on various devices.

- **Hide/Show Elements:** Utilize CSS to selectively hide or show elements based on screen size.

Remember to test your website on real devices or use browser developer tools to simulate different screen sizes.

Please go through it against tomorrow, as we'd be working a lot with this tool in the coming weeks. Happy weekend & coding!
