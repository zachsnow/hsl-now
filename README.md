# hsl-now

A simple HSL "clock". I saw an RGB one that didn't transition very smoothly through
different colors (as that wasn't the point), so I thought "how might I make one that does".
I'm sure it's been done every which way from Sunday, but that's ok.

Just for fun.

## About

The *hue* component is set based on the time of day, linearly interpolating from
`0` through `360`. The *lightness* component is also set based on the time of day,
but it linearly interpolates from `0%` to `50%` and then back down to `0%` again.
The *saturation* component is based on the day of the year, and interpolates
from `50%` to `100%` and then back down to `50%`, the idea being that in the
winter (in the northern hemisphere) the colors are less saturated, while in the
summer they are more saturated.

## Demo

(If you can call it that).

[now.zachsnow.com](http://now.zachsnow.com)
