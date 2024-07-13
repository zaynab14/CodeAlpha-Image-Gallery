#Image Gallery Project
#Overview
This project is an image gallery built with HTML, CSS, and JavaScript. The gallery showcases a collection of images categorized into "Dogs", "Cats", and "Rabbits". Users can filter the images by these categories using buttons. The project utilizes Isotope for filtering and jQuery for DOM manipulation.

#Features
Responsive Design: The gallery layout adjusts to different screen sizes.
Filtering: Users can filter images by category.
Hover Effects: Smooth hover effects on images and overlay with a "VIEW MORE" link.
Styled Buttons: Buttons change color when active, providing a clear visual cue.
Technologies Used
1. HTML
2. CSS
3. JavaScript
4. jQuery
5. Isotope (for filtering and layout)

#Dependencies
. jQuery 3.7.1
. Isotope 3.0.6
. Font Awesome 6.1.1
These dependencies are included via CDN links in the index.html file.

#Customization
#Adding New Categories:

Add a new button with a data-filter attribute matching the new category class.
Add images within a div with the new category class in the gallery section.
Styling:

Update the style.css file to modify the design, such as colors, fonts, and layout.

#Code Explanation

#HTML (index.html)
The structure consists of a header, a section for buttons to filter images, and a gallery section containing the images.
The buttons have data-filter attributes used by Isotope for filtering.
Each image is wrapped in a div with a corresponding category class (Dogs, Cats, Rabbits).

#CSS (style.css)
Basic reset and box-sizing settings are applied.
Custom properties (CSS variables) are used for consistent theming.
Styles are defined for layout, button states, hover effects, and responsiveness.

#JavaScript (index.html)
jQuery is used to initialize the Isotope plugin.
Event listeners are added to the filter buttons to update the active state and filter the images based on the selected category.

#Credits
Images used are placeholders. Replace them with your own images by updating the src attribute in the img tags.
Font Awesome icons are used for additional styling options.
