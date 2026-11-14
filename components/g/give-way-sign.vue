<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bmpuag-en"/><path class="j5uu9g2bg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:give-way-sign" /></template>
<style>
.bmpuag-en {
  d: path("M5.483 3.5h13.034a1.75 1.75 0 0 1 1.528 2.604l-6.517 11.662a1.75 1.75 0 0 1-3.056 0L3.955 6.104A1.75 1.75 0 0 1 5.483 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5uu9g2bg {
  d: path("M10.105 6.5h3.79a1.5 1.5 0 0 1 1.297 2.253l-1.895 3.263a1.5 1.5 0 0 1-2.594 0L8.808 8.753A1.5 1.5 0 0 1 10.105 6.5");
}

</style>
