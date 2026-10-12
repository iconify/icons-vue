<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xr9pq559y"/><path class="k3yr6qbrd"/><path class="ywhqqkbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:khussa" /></template>
<style>
.k3yr6qbrd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 15c2.25 0 4.5-1 6-2.75");
}

.xr9pq559y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.75c0 2 1.25 3.25 3.25 3s3-1.25 4.5-3.25h6.75a3.25 3.25 0 0 1 3.25 3.25v3.5a1.25 1.25 0 0 1-1.25 1.25h-11C4.75 17.5 3 14.75 3 9.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ywhqqkbci {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 14.5h.01m2.49 0h.01");
}

</style>
