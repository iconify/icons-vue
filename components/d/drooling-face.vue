<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGcOeGFdue" cx="64" cy="-3303.56" r="56.96" fx="64" fy="-3303.56" gradientTransform="matrix(1 0 0 -1 0 -3238)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><linearGradient id="SVGLT4RgbRJ" x1="69.75" x2="69.75" y1="123.6" y2="89.65" gradientUnits="userSpaceOnUse"><stop offset=".46" class="v1-56mb1l"/><stop offset="1" class="r5vbxk1ae"/></linearGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGcOeGFdue)" class="nhaqzgrbw"/><path class="uxqy5qb9b"/></g><path class="hxmbstb8s"/><g class="wj4kgr0on"><path class="idncuebpo"/><path fill="url(#SVGLT4RgbRJ)" class="r0zgh3bza"/><path class="v6pfkcbgk"/></g><path class="violqlh8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:drooling-face" /></template>
<style>
.hxmbstb8s {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M29.91 57.88c-1.61-1.49-1.36-4.01.51-5.34c2.37-1.69 5.81-3.75 9.68-4.8c3.87-1.06 7.87-1.04 10.77-.79c2.28.2 3.78 2.24 3.15 4.34c-.51 1.69-2.24 2.83-4.07 2.67c-2.19-.2-5.22-.23-8 .53c-2.79.76-5.37 2.33-7.16 3.62c-1.5 1.08-3.57.97-4.87-.23Zm68.18 0c1.61-1.49 1.36-4.01-.51-5.34c-2.37-1.69-5.81-3.75-9.68-4.8c-3.87-1.06-7.87-1.04-10.77-.79c-2.28.2-3.78 2.24-3.15 4.34c.51 1.69 2.24 2.83 4.07 2.67c2.19-.2 5.22-.23 8 .53c2.79.76 5.37 2.33 7.16 3.62c1.5 1.08 3.57.97 4.87-.23Z");
}

.idncuebpo {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64 96.7c-13.25 0-22.71-7.8-25.55-12.14c-1.1-1.67-1.31-3.49-.58-4.86c.56-1.03 1.57-1.62 2.78-1.62c.4 0 .83.07 1.25.2c6.68 2.09 12.52 5.14 22.1 5.14s15.44-3.05 22.1-5.14c.43-.13.85-.2 1.25-.2c1.21 0 2.22.59 2.78 1.62c.74 1.37.52 3.18-.58 4.86C86.7 88.89 77.25 96.7 64 96.7");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.nhaqzgrbw {
  d: path("M64 121.46c-27.9 0-58-17.5-58-55.9s30.1-55.9 58-55.9c15.5 0 29.8 5.1 40.4 14.4c11.5 10.2 17.6 24.6 17.6 41.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r0zgh3bza {
  d: path("M82.34 109.5c-.96-4.65-2.58-9.06-2.21-11.97c.74-5.7 4.18-7.67 4.18-7.67s-2.27-.76-5.26.61c-3.28 1.5-1.86 2.26-6.91 3.3c-4.25.88-6.7-1.31-11.54-.47c-4.34.76-5.41 2.22-5.41 2.22s2.97 1.02 7.32 1.53c8.01.94 7 8.03 6.43 10.99c-1.14 5.81-2.68 15.93 6.88 15.56c6.92-.27 7.9-7.48 6.54-14.1Z");
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.uxqy5qb9b {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 32.33c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37-7.35-48.18-22.94c10.76 17.66 31 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5c11.5-10.2 17.6-24.5 17.6-41.4c0-12.74-3.47-24.06-10.11-33.23");
}

.v1-56mb1l {
  stop-color: var(--svg-color--29b6f6, #29b6f6);
}

.v6pfkcbgk {
  fill: var(--svg-color--81d4fa, #81d4fa);
  d: path("M70.99 118.01c1.07 1.65 3.49 1.34 3.49-1.4c0-1.75-.36-10.77-1.86-9.51c-2.45 2.05-3.15 8.58-1.63 10.91");
}

.violqlh8x {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M30.61 39.96c-1.33 1.79-4.25.47-3.27-1.73c2.08-4.44 6.05-8.39 11.27-10.38c1.83-.77 3.84-1.22 5.67-1.32c2.5-.1 2.61 3.07.55 3.62l-.13.05c-5.81 1.59-10.85 5.23-14.09 9.76m66.83-7.13c1.43 1.72 4.27.22 3.17-1.91c-2.33-4.31-6.51-8.03-11.84-9.72c-1.87-.66-3.9-1-5.74-1c-2.51.04-2.43 3.22-.35 3.65l.14.04c5.89 1.26 11.12 4.61 14.62 8.95Z");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
