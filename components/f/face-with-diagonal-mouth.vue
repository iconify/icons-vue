<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGXFsl5baB" cx="64" cy="9420.18" r="56.96" fx="64" fy="9420.18" gradientTransform="translate(0 -9356.18)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGXFsl5baB)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="q86_pqb3e"/><path class="p0zhchb8b"/><path class="ql2hc5bwu"/><path class="xq7vhqb3r"/><path class="rmmnpyhiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-diagonal-mouth" /></template>
<style>
.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.p0zhchb8b {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.44 50.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.q86_pqb3e {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M44.83 47.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.ql2hc5bwu {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.17 47.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.rmmnpyhiw {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M91 84.61L43.03 98.72c-2.12.62-4.34-.59-4.97-2.71s.59-4.34 2.71-4.97l47.97-14.11c2.12-.62 4.34.59 4.97 2.71s-.59 4.34-2.71 4.97");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.xq7vhqb3r {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.78 50.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1.01-1.45.68-2.97-.36-3.69");
}

</style>
