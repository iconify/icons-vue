<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGYeJeve9K" cx="64" cy="-1456" r="56.96" fx="64" fy="-1456" gradientTransform="matrix(1 0 0 -1 0 -1392)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGYeJeve9K)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="yxfk0ab6p"/><path class="fixygoh0d"/><path class="b-_b-ibcj"/><path class="ijvulo1lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:anguished-face" /></template>
<style>
.b-_b-ibcj {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.fixygoh0d {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.ijvulo1lw {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.yxfk0ab6p {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M52.7 104.1c-3.4 0-6.5-1.8-8.2-4.6s-1.5-6.2.4-8.9c4.3-6 10.9-9.2 19.1-9.2s14.8 3.2 19.1 9.2c1.9 2.7 2.1 6 .4 8.9c-1.7 2.8-4.8 4.6-8.2 4.6c-1.1 0-2.1-.2-3.1-.5c-2.7-.9-5.4-1.3-8.2-1.3s-5.5.4-8.2 1.3c-1 .3-2.1.5-3.1.5m30.57-71.69h-.1c-2.21-.06-2.76-3.24-.29-3.67c1.84-.3 3.85-.27 5.83.05c5.54.82 10.23 3.87 13.22 7.72c1.49 1.98-1.14 3.9-2.79 2.4c-4.21-3.69-9.87-6.24-15.87-6.51Zm-38.54 0h.1c2.21-.06 2.76-3.24.29-3.67c-1.84-.3-3.85-.27-5.83.05c-5.54.82-10.23 3.87-13.22 7.72c-1.49 1.98 1.14 3.9 2.79 2.4c4.21-3.69 9.87-6.24 15.87-6.51Zm.09 18.63c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

</style>
