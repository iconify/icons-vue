<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGzN46zeZf" cx="64" cy="-934" r="56.96" fx="64" fy="-934" gradientTransform="matrix(1 0 0 -1 0 -870)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGzN46zeZf)" class="uuo0vn6ns"/><path class="ba4-6rbxq"/></g><path class="wm1qsn37d"/><path class="g46dm_7-b"/><path class="mi9ev4b1s"/><path class="sy8o2-b4l"/><path class="r5-givbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:hushed-face" /></template>
<style>
.ba4-6rbxq {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37-7.35-48.18-22.94c10.76 17.66 31 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.g46dm_7-b {
  fill: var(--svg-color--896024, #896024);
  d: path("M41.94 51.97a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mi9ev4b1s {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M85.67 48.04c-4.19 0-8 3.54-8 9.42s3.81 9.41 8 9.41s8-3.54 8-9.41s-3.79-9.42-8-9.42");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r5-givbdx {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M28.47 39.1c-.7.73-1.87.76-2.6.05c-.66-.63-.75-1.66-.22-2.4c1.13-1.63 2.52-3.05 4.12-4.22c4.19-3.23 9.44-4.76 14.71-4.28c2.49.31 2 3.49-.21 3.7c-5.94.47-11.53 3-15.8 7.15m71.06.23c.7.73 1.87.76 2.6.05c.66-.63.75-1.66.22-2.4a17.3 17.3 0 0 0-4.07-4.17a20.92 20.92 0 0 0-14.71-4.27c-2.48.31-2 3.48.21 3.69c5.92.47 11.48 2.98 15.75 7.1");
}

.sy8o2-b4l {
  fill: var(--svg-color--896024, #896024);
  d: path("M85.29 51.97a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.wm1qsn37d {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M76.8 93.5c0 7.07-5.73 12.8-12.8 12.8s-12.8-5.73-12.8-12.8S56.93 80.7 64 80.7c7.05-.02 12.78 5.67 12.8 12.72zM42.33 48.04c-4.19 0-8 3.54-8 9.42s3.81 9.41 8 9.41s8-3.54 8-9.41s-3.81-9.42-8-9.42");
}

</style>
