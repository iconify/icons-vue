<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGAedLueNE" cx="64" cy="64" r="56.96" fx="64" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><linearGradient id="SVGjTy1IbPN" x1="64" x2="64" y1="-1511.9" y2="-1400.1" gradientTransform="matrix(1 0 0 -1 0 -1392)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="lfxua2bme"/><stop offset="1" class="zvhoujbdx"/></linearGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGAedLueNE)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/><path fill="url(#SVGjTy1IbPN)" class="uuo0vn6ns"/></g><path class="e79sf1b4m"/><path class="fixygoh0d"/><path class="b-_b-ibcj"/><path class="p8jh-hbya"/><path class="ellv6smfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:fearful-face" /></template>
<style>
.b-_b-ibcj {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.e79sf1b4m {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M44.82 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.ellv6smfg {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M79.47 88.57c-2.67-2.5-7.62-5.72-15.46-5.72s-12.6 3.22-15.46 5.72c-3.91 3.42-5.18 8.08-3.46 10.88c2.06 3.36 6 2.69 8.44 2.36s6.5-1 10.47-1s8.03.67 10.47 1s6.38 1 8.44-2.36c1.72-2.8.33-7.33-3.46-10.88Zm3.8-56.16h-.1c-2.21-.06-2.76-3.24-.29-3.67c1.84-.3 3.85-.27 5.83.05c5.54.82 10.23 3.87 13.22 7.72c1.49 1.98-1.14 3.9-2.79 2.4c-4.21-3.69-9.87-6.24-15.87-6.51Zm-38.54 0h.1c2.21-.06 2.76-3.24.29-3.67c-1.84-.3-3.85-.27-5.83.05c-5.54.82-10.23 3.87-13.22 7.72c-1.49 1.98 1.14 3.9 2.79 2.4c4.21-3.69 9.87-6.24 15.87-6.51Z");
}

.fixygoh0d {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.lfxua2bme {
  stop-color: var(--svg-color--40c0e7, #40c0e7);
  stop-opacity: 0;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.p8jh-hbya {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 54.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
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

.zvhoujbdx {
  stop-color: var(--svg-color--5f7aff, #5f7aff);
}

</style>
