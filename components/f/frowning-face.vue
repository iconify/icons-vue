<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGLQb4bblj" cx="64" cy="-1160" r="56.96" fx="64" fy="-1160" gradientTransform="matrix(1 0 0 -1 0 -1096)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><path fill="url(#SVGLQb4bblj)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/><path class="howg8lbqv"/><path class="bycmrbc9p"/><path class="jf00rc3go"/><path class="xp5evsbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:frowning-face" /></template>
<style>
.bycmrbc9p {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 45.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.howg8lbqv {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M91.01 89.03C84.98 78.43 75.21 72.01 64 72.01s-20.98 6.42-27.01 17.02c-.86 1.51-1.42 4.09-.41 4.68c1.17.68 2.57-.69 3.56-1.91c7.51-9.21 16.9-12.43 23.86-12.43s16.35 3.22 23.86 12.43c1 1.22 2.4 2.6 3.56 1.91c1.02-.59.45-3.17-.41-4.68M44.82 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.jf00rc3go {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
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

.xp5evsbxg {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

</style>
