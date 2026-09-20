<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGYeJeve9K" cx="64" cy="-1456" r="56.96" fx="64" fy="-1456" gradientTransform="matrix(1 0 0 -1 0 -1392)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGYeJeve9K)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="jtritcxya"/><path class="cbyqwpllm"/><path class="rgje4ieag"/><path class="cx8a2fcyp"/><path class="n7-mobcvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:frowning-face-with-open-mouth" /></template>
<style>
.cbyqwpllm {
  fill: var(--svg-color--896024, #896024);
  d: path("M43.43 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.cx8a2fcyp {
  fill: var(--svg-color--896024, #896024);
  d: path("M83.79 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.jtritcxya {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M43.82 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.n7-mobcvx {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M84.54 89.2c-4.1-5.87-11.26-8.07-20.54-8.07s-16.44 2.2-20.54 8.07c-2.74 3.93-2.4 8.29.32 11.42c2.35 2.7 6.5 2.81 8.93 2.31s7.44-1.31 11.29-1.31s8.86.82 11.29 1.31c2.43.5 6.59.39 8.93-2.31c2.72-3.13 3.06-7.5.32-11.42");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.rgje4ieag {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M84.18 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
