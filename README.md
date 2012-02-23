# Modal.js
Display an object (eg a form) in a popup (or modal) window on a site.

Works in IE7+ (popup displays in IE6 but the overlay isn't shown).

## Requirements
jQuery 1.5 or better.
(Note: currently uses .live() for compatibility with old jQuery versions, but this can be updated to on() for jQuery 1.7 onwards).

## Usage
$('.trigger').modal('#form');

The form to display needs to already exist on the page, and there can only be one on the page (so use an id to target it).

You can have several triggers for each form, and you can have as many different modal windows as you like
e.g. 

$('.trigger1').modal('#form1');

$('.trigger2').modal('#form2');
