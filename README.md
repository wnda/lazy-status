# lazy-status
This is probably the laziest way to display a status page for websites/web apps that you manage.

It works by attaching functions to the `onload` and `onerror` events of an image downloaded from a website or web app. Using this method, you can technically check the status of any website or web app. My implementation also times the network latency using the `performance.timing.navigationStart` API available in modern browsers.

The functions I have written replace the image downloaded from each website with an SVG icon indicating online or offline.
