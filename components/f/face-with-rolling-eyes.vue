<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><clipPath id="SVGwhfGAb4t"><use href="#SVGBFFzyoON" class="wj4kgr0on"/></clipPath><clipPath id="SVGfuamQ93Z"><use href="#SVGujxi5doL" class="wj4kgr0on"/></clipPath><path id="SVGBFFzyoON" class="kbsqakbwa"/><path id="SVGujxi5doL" class="d9e7iccqb"/><radialGradient id="SVGAedLueNE" cx="64" cy="64" r="56.96" fx="64" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGAedLueNE)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="tc_akqbsb"/><use href="#SVGBFFzyoON"/><g clip-path="url(#SVGwhfGAb4t)"><circle class="fonghbbjp"/></g><path class="xxdwt6epq"/><use href="#SVGujxi5doL"/><g clip-path="url(#SVGfuamQ93Z)"><circle class="lo5hs6b-f"/></g><path class="grom73t3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-rolling-eyes" /></template>
<style>
.d9e7iccqb {
  fill: var(--svg-color--fff, #fff);
  d: path("M94.68 42.13c-.34-.19-.68-.38-1.03-.54c-4.39-2.03-9.21-1.96-13.35-.23c-3.71 1.55-6.87 4.42-8.69 8.35c-3.84 8.33-.21 18.2 8.12 22.04s18.2.21 22.04-8.12c3.68-7.97.49-17.34-7.09-21.5");
}

.fonghbbjp {
  cx: 42.28px;
  cy: 44.62px;
  r: 7.31px;
  fill: var(--svg-color--422b0d, #422b0d);
}

.grom73t3w {
  fill: var(--svg-color--f4a223, #f4a223);
  d: path("M70.23 56.94c.65 4.32 2.78 8.07 5.74 10.72c1.51 1.29 3.19 2.37 5.03 3.03c1.82.7 3.75 1.07 5.69 1.05c3.89.04 7.73-1.45 10.72-4.07c2.96-2.65 5.09-6.4 5.74-10.72h.2c.03 4.37-1.75 8.72-4.84 11.82c-3.07 3.12-7.42 4.94-11.82 4.94c-4.39 0-8.74-1.82-11.82-4.94c-3.1-3.1-4.88-7.45-4.84-11.82h.2Z");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.kbsqakbwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M50.05 42.13c-.34-.19-.68-.38-1.03-.54c-4.39-2.03-9.21-1.96-13.35-.23c-3.71 1.55-6.87 4.42-8.69 8.35c-3.84 8.33-.21 18.2 8.12 22.04s18.2.21 22.04-8.12c3.68-7.97.49-17.34-7.09-21.5");
}

.lo5hs6b-f {
  cx: 86.91px;
  cy: 44.62px;
  r: 7.31px;
  fill: var(--svg-color--422b0d, #422b0d);
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

.tc_akqbsb {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M75.4 99.1h-22c-2.2 0-4-1.8-4-4s1.8-4 4-4h22c2.2 0 4 1.8 4 4s-1.8 4-4 4");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.xxdwt6epq {
  fill: var(--svg-color--f4a223, #f4a223);
  d: path("M25.65 56.94c.65 4.32 2.78 8.07 5.74 10.72c1.51 1.29 3.19 2.37 5.03 3.03c1.82.7 3.75 1.07 5.69 1.05c3.89.04 7.73-1.45 10.72-4.07c2.96-2.65 5.09-6.4 5.74-10.72h.2c.03 4.37-1.75 8.72-4.84 11.82c-3.07 3.12-7.42 4.94-11.82 4.94c-4.39 0-8.74-1.82-11.82-4.94c-3.1-3.1-4.88-7.45-4.84-11.82h.2Z");
}

</style>
