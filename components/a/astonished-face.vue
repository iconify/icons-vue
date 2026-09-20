<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGYeJeve9K" cx="64" cy="-1456" r="56.96" fx="64" fy="-1456" gradientTransform="matrix(1 0 0 -1 0 -1392)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGYeJeve9K)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="mko3xkb_t"/><path class="zs4zuj3le"/><g class="wj4kgr0on"><path class="y97on6bln"/><path class="f6_caibdv"/><path class="bxrm3bbjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:astonished-face" /></template>
<style>
.bxrm3bbjv {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M76.01 86.7c-.68-3.13-2.19-5.79-4.37-7.64c-2.17-1.84-4.88-2.87-7.63-2.86c-2.75 0-5.46 1.02-7.63 2.86c-2.17 1.86-3.69 4.51-4.37 7.64c-.6-3.15.41-6.72 2.71-9.29c2.24-2.62 5.75-4.24 9.29-4.21c3.54-.02 7.05 1.59 9.29 4.21c1.14 1.29 1.97 2.83 2.45 4.43c.46 1.61.54 3.29.27 4.86Z");
}

.f6_caibdv {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M52.05 85.93c-.02.26-.04.51-.04.77v11.8c0 6.6 5.4 12 12 12s12-5.4 12-12V86.7c0-.21-.02-.42-.03-.63c-3.64.41-7.45.63-11.37.63c-4.35 0-8.56-.27-12.56-.77");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mko3xkb_t {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M45.65 30c2.3.2 3.2-2.9.8-3.6c-1.8-.5-3.8-.7-5.8-.6c-5.6.2-10.6 2.7-14 6.2c-1.7 1.8.7 4 2.5 2.7c4.6-3.2 10.5-5.1 16.5-4.7m36.6 0c6.1-.4 12 1.5 16.6 4.7c1.8 1.3 4.2-.9 2.5-2.7c-3.4-3.5-8.5-6-14-6.2c-2-.1-4 .1-5.8.6c-2.4.7-1.5 3.8.7 3.6m1.65 11.7c3.8 0 7.3 4.4 7.3 11.8s-3.5 11.8-7.3 11.8s-7.3-4.4-7.3-11.8s3.4-11.8 7.3-11.8m-39.4 0c-4.1 0-7.7 4.4-7.7 11.8s3.7 11.8 7.7 11.8s7.7-4.4 7.7-11.8s-3.7-11.8-7.7-11.8");
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

.y97on6bln {
  fill: var(--svg-color--fff, #fff);
  d: path("M64.61 86.7c3.92 0 7.73-.22 11.37-.63c-.33-6.31-5.58-11.37-11.97-11.37s-11.56 4.99-11.96 11.23c4 .5 8.21.77 12.56.77");
}

.zs4zuj3le {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.48 45.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69m39.03 0c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

</style>
