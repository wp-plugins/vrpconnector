=== Plugin Name ===
Contributors: Houghtelin
Tags: Vacation Rental Platform, Gueststream, VRP Connector, ISILink, HomeAway, Escapia, Barefoot, VRMGR
Requires at least: 3.0.1
Tested up to: 4.2.2
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Vacation Rental Platform Connector allows you to display and book your vacation rental properties on your site.

== Description ==
The Vacation Rental Property Connector plugin by Gueststream, Inc. allows you to sync all of your vacation rental
properties from HomeAway, Escapia, ISILink (First Resort, Property Plus, V12) , Barefoot, RNS (Resort Network), VRMGR, RTR and other property management software to your website
allowing potential guests to search, sort, compare and book your rental properties right from your website.

= Example Sites =
* http://www.grandcaymanvillas.net
* http://www.mauihawaiivacations.com
* http://www.tellurideluxury.com
* http://www.columbiatelluride.com

== Installation ==
1. Install the plugin from the WordPress.org Plugin Directory here https://wordpress.org/plugins/vrpconnector/
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to Wordpress Admin > Settings > VRP and enter your Gueststream.net API key
1. Begin adding the available shortcodes to your posts and pages as desired.
The following shortcodes are available for use throughout your website.
To use them simply add them to the page/post content.

* [vrpSearchForm] - Will display an advanced search for users to search your properties.
* [vrpUnits] - Displays a list of all enabled units
* [vrpSearch] - Requires additional attributes to display units according to the values set. This short code effectively produces the results of performing an availability search.

More detailed instructions for using shortcodes, theming the VRP pages and using the plugin can be found
 at the VRPConnector's Wiki page here: https://github.com/Gueststream-Inc/VRPConnector/wiki

== Frequently Asked Questions ==
= What property management software(s) does the VRP Connector support? =

HomeAway, ISILink, Escapia, Barefoot, RNS.

= Does the VRP Connector require an account with Gueststream.net? =
Yes, Gueststream.net provides the back-end service of interfacing with many property management software APIs that allows
you to seamlessly connect your website to your property management software data.

== Screenshots ==
1. Out of the box unit page.

== Changelog ==
= 1.0.5 =
* Fixed Parse Error for PHP 5.2 and enhanced PHP version notice.

= 1.0.4 =
* Plugin settings link (visible after VRPConnector plugin is activated) added to plugins list.
* Shortcode examples added to installation documentation.
* Settings page renamed from VRP to VRPConnector

= 1.0.3 =
* ShortCodes can be used in Widget Text
* Advanced Search Form posts to regular search instead of complex search by default.
* Unit Thumbnail photos with URL's containing spaces %20 in them now display correctly.

= 1.0.2 =
* Fixed var declaration inside of a hash map.

= 1.0.1 =
* Fixed bug in unit page mapping JS.

= 1.0.0 =
* Better support for Specials themes and added [vrpSpecials] shortcode.

= 0.09 =
* Added ability for users to favorite units, view & share their list of favorites.

= 0.08 =
* Added caching for all API calls
* Removed requirement for custom permalink structure.

= 0.06 =
* Added [vrpFeaturedUnit] short code support.

= 0.01 =
* Initial Release

== Upgrade Notice ==
= 0.10 =
* Display Specials by category or individually with the use of shortcodes.

= 0.09 =
* Users can now build a list of favorite units.

= 0.08 =
* Now custom permalink structures work!
* Established caching for a much faster guest experience.

= 0.07 =
* Added [vrpFeaturedUnit] shortcode support.