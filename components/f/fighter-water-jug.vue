<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wlf20px0y"/><path class="p5orp9ctt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fighter-water-jug" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5orp9ctt {
  d: path("M6.5 15q2.75-1.75 5.5 0t5.5 0");
}

.wlf20px0y {
  d: path("M6.875 8.5h10.25a4.375 4.375 0 0 1 4.375 4.375v3.75A4.375 4.375 0 0 1 17.125 21H6.875A4.375 4.375 0 0 1 2.5 16.625v-3.75A4.375 4.375 0 0 1 6.875 8.5m-.625-4h2.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 8.75 8.5h-2.5A1.75 1.75 0 0 1 4.5 6.75v-.5A1.75 1.75 0 0 1 6.25 4.5m6.75 4v-4a1 1 0 0 1 1-1h4.5a1 1 0 0 1 1 1v4");
}

</style>
