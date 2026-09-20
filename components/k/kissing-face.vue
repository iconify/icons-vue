<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGrF3uwbnJ" cx="64" cy="-272" r="56.96" fx="64" fy="-272" gradientTransform="matrix(1 0 0 -1 0 -208)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGrF3uwbnJ)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="mhp_0ccua"/><path class="g7kp-qbxs"/><path class="i4_w_crub"/><path class="kf9mtibbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:kissing-face" /></template>
<style>
.g7kp-qbxs {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.83 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.i4_w_crub {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.58 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.kf9mtibbu {
  fill: var(--svg-color--896024, #896024);
  d: path("M83.19 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mhp_0ccua {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M74.03 86.03s2.86-2.32 3.05-5.86c.19-3.61-.73-4.84-1.91-6.41c-2.76-3.68-10.45-2.78-10.45-2.78c-2.06.07-4.45 1.06-4.15 3.44c.13 1.06 1.41 2.36 2.87 2.71c3.03.73 7.37.01 7.49 3.09c.14 3.46-5.18 2.04-5.6 5.7c-.43 3.66 5.61 3.19 5.6 5.71c0 1.93-1.98 2.26-4.07 2.7c-1.79.37-5.23.93-5.51 2.99s.9 4.57 5.74 3.84c7.62-1.15 10.17-5.32 10.17-7.88c0-4.8-3.24-7.23-3.24-7.23ZM45.22 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
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

</style>
