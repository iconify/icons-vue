<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfenysb5q"/><path class="gp6e5zbzl"/><path class="zytl48bhh"/><path class="rhu00w8ze"/><path class="vdru2ys6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heatmap-taps" /></template>
<style>
.gp6e5zbzl {
  fill: currentColor;
  d: path("M9 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rfenysb5q {
  d: path("M9.875 2.5h4.25A4.375 4.375 0 0 1 18.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 17.125V6.875A4.375 4.375 0 0 1 9.875 2.5");
}

.rhu00w8ze {
  fill: currentColor;
  d: path("M13.25 14.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

.vdru2ys6p {
  d: path("M12.25 14.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M14 10.75v1m3.25 2.75h-1m0-2.25l-.75.75M11 18h2.5");
}

.zytl48bhh {
  d: path("M7.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
