<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGrF3uwbnJ" cx="64" cy="-272" r="56.96" fx="64" fy="-272" gradientTransform="matrix(1 0 0 -1 0 -208)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGcATICcjG" cx="111.32" cy="785.83" r="25.66" fx="111.32" fy="785.83" gradientTransform="matrix(1 0 0 1.54 0 -1190.33)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="v1-56mb1l"/><stop offset="1" class="r5vbxk1ae"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGrF3uwbnJ)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><g class="wj4kgr0on"><path fill="url(#SVGcATICcjG)" class="kf5ekstpc"/><path class="h0qcpdk1g"/></g><path class="pq1o8qp_w"/><g class="wj4kgr0on"><path class="wftzaolpz"/><path class="ffqs2pb6l"/><path class="u-y3wttnn"/><path class="ct_8dkr3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:grinning-face-with-sweat" /></template>
<style>
.ct_8dkr3b {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M102.75 72.73c-1.33-2.46-4.19-3.55-7.19-2.61c-8.96 2.8-20.46 4.42-31.59 4.43c-11.12-.01-22.63-1.63-31.59-4.43c-2.99-.93-5.81.14-7.14 2.6c-1.36 2.52-.37 5.42.77 7.94c.52 1.14 1.09 2.24 1.71 3.31c0 0-2.13-7.8-.28-10.06c.76-.92 2.57-1.6 4.63-1c9.2 2.69 20.79 4.26 31.89 4.37s22.91-1.87 32.34-4.76c2.11-.65 3.43.48 4.19 1.4c1.85 2.26-.28 10.07-.28 10.07c.62-1.07 1.24-2.16 1.76-3.3c1.14-2.51 2.13-5.42.77-7.94Z");
}

.ffqs2pb6l {
  fill: var(--svg-color--ed7770, #ed7770);
  d: path("M64.05 92.86c-13.11-.32-17.18 6.82-17.42 7.14c2.4 1.22 9.9 3.34 17.12 3.38s14.53-2.01 16.88-3.04c-.17-.33-3.48-7.16-16.59-7.47Z");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.h0qcpdk1g {
  fill: var(--svg-color--81d4fa, #81d4fa);
  d: path("M117.53 46.51c-1.47 2.27-4.8 1.84-4.8-1.93c0-2.41.49-14.79 2.56-13.06c3.37 2.82 4.33 11.78 2.24 14.99");
}

.kf5ekstpc {
  d: path("M110.5 53.71c-6.5 0-11.5-6.3-11.5-11.7c0-3.8 1.7-8.2 4.1-14.3c.3-.9.7-1.8 1.1-2.8c1.14-2.86 2.15-5.96 3.69-8.64c1.05-1.83 3.71-1.83 4.71.03c1.43 2.63 2.41 5.49 3.9 8.81c4.2 9.4 5.4 13.2 5.4 17c.1 5.3-5 11.6-11.4 11.6");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.pq1o8qp_w {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M48.82 57.99c-1.1-1.35-2.59-3.24-4.39-3.62c-.04 0-.08-.01-.13 0h-.04h.27c-1.57-.23-3.7 2.23-4.8 3.55c-1.33 1.8-4 2.23-5.85.88c-2.6-2.09-1.37-4.73.04-7.5c1.55-3.02 5.66-6.05 9.51-6.16c.94-.09 1.92-.01 2.85.15c5.08.86 8.98 5.34 9.79 9.96c.7 3.97-4.99 5.84-7.26 2.75Zm39.49 0c-.14-.18-.35-.45-.58-.75c-1.03-1.07-2.28-2.61-3.81-2.87c-.04 0-.08-.01-.13 0h-.04h.27l-.55.02c-.14 0-.05.01-.04.01h.07c.08-.03 0 0-.02 0c-.03 0-.07 0-.11.03c-1.75.48-3.3 2.57-4.37 3.77c-2.31 2.88-7.77.96-7.1-2.86c.77-4.84 5.49-9.96 11.03-10.19c6.08-.6 11.75 4.55 12.64 10.11c.71 3.97-4.99 5.84-7.26 2.75Z");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.u-y3wttnn {
  fill: var(--svg-color--fff, #fff);
  d: path("M95.56 71.15c-8.96 2.8-20.66 4.67-31.79 4.68c-11.12-.01-21.98-1.72-30.94-4.53c-2.99-.93-5.28-.93-6.6 1.54c-.21.39-.72 1.42-.26 1.59c12.1 6.17 25.16 8.93 38.8 8.93s25.64-2.55 37.33-8.21c.47-.2-.15-1.71-.48-2.32c-1.33-2.46-3.07-2.63-6.07-1.69Z");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.v1-56mb1l {
  stop-color: var(--svg-color--29b6f6, #29b6f6);
}

.wftzaolpz {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M101.54 72.9c-1.33-2.46-3.83-2.77-6.83-1.83c-8.96 2.8-19.52 4.23-30.65 4.25c-11.12-.01-22.85-1.53-31.81-4.33c-2.99-.93-4.59-.3-5.91 2.17c-1.36 2.52-1.45 4.99-.31 7.5c6.42 14.1 21.84 23.01 38.04 22.59c18.63-.48 31.45-8.49 37.87-22.59c1.14-2.51.96-5.23-.4-7.75Z");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
