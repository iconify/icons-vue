<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cqjj-tb3s"/><path class="m00hj4ptx"/><path class="qr7i3605k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:granite-countertop" /></template>
<style>
.cqjj-tb3s {
  d: path("M4 11h11a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 15 18H4a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 4 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m00hj4ptx {
  d: path("m2.5 11l5-5h14v7l-5 5m0-7l5-5");
}

.qr7i3605k {
  d: path("M9.75 8.5a2.75 1 0 1 0 5.5 0a2.75 1 0 1 0-5.5 0M14 6V3.5h-2.5M5.5 14h.01M9 15.5h.01m3.49-1.75h.01");
}

</style>
