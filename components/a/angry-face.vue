<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGEjWQ7d9e" cx="64" cy="-2710" r="56.96" fx="64" fy="-2710" gradientTransform="matrix(1 0 0 -1 0 -2646)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGEjWQ7d9e)" class="uuo0vn6ns"/><path class="ba4-6rbxq"/></g><g class="wj4kgr0on"><path class="yblfqtbmt"/><path class="qtt4gs5qp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:angry-face" /></template>
<style>
.ba4-6rbxq {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37-7.35-48.18-22.94c10.76 17.66 31 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.qtt4gs5qp {
  fill: var(--svg-color--896024, #896024);
  d: path("M47.36 69.55a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3m32.51 0a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3");
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

.yblfqtbmt {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.2 104.24a2.2 2.2 0 0 1-.89-.62c-9.73-10.11-25.82-10.42-35.93-.69c-.23.23-.47.46-.69.69c-.24.28-.55.49-.89.62c-.75.28-1.6.12-2.2-.41c-.59-.52-.79-1.35-.49-2.08C45.09 94.1 53.95 88.1 64 88.1s18.91 6 21.89 13.64c.3.73.1 1.56-.49 2.08c-.6.53-1.45.69-2.2.42M57.38 69.92c-2.24-2.82-11.47-8.24-14.8-9.82c-1.24-.57-2.53-1.03-3.85-1.37c-.24-.07-.5-.1-.75-.1a2.87 2.87 0 0 0-2.74 2.29a2.92 2.92 0 0 0 1.67 3.32c1.57.77 4.31 2.23 7.15 3.84a7.83 7.83 0 0 0-3.82 6.73v1.46c0 4.14 3.36 7.5 7.5 7.5s7.5-3.36 7.5-7.5v-1.63c1.07-.07 2.03-.71 2.5-1.67c.49-1 .35-2.19-.36-3.05m35.38-9a2.87 2.87 0 0 0-2.79-2.27c-.25 0-.51.03-.75.1c-1.32.33-2.61.79-3.85 1.35c-3.33 1.56-12.56 7-14.8 9.8a2.84 2.84 0 0 0-.33 3.07c.48.97 1.43 1.6 2.51 1.67v1.63c0 4.14 3.36 7.5 7.5 7.5s7.5-3.36 7.5-7.5v-1.46c0-2.75-1.45-5.3-3.81-6.71c2.84-1.61 5.58-3.07 7.15-3.84c1.29-.56 2-1.97 1.67-3.34");
}

</style>
