<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aibcu1dvr"/><path class="xihuptbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coverage-map" /></template>
<style>
.aibcu1dvr {
  d: path("m3.122 5.069l4.772-1.836a1.75 1.75 0 0 1 1.217-.015l5.778 2.064a1.75 1.75 0 0 0 1.217-.015l3.516-1.352A1.75 1.75 0 0 1 22 5.548v11.75a1.75 1.75 0 0 1-1.122 1.633l-4.772 1.836a1.75 1.75 0 0 1-1.217.015l-5.778-2.064a1.75 1.75 0 0 0-1.217.015l-3.516 1.352A1.75 1.75 0 0 1 2 18.452V6.702a1.75 1.75 0 0 1 1.122-1.633M12 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xihuptbzt {
  d: path("M9.5 9.5a3.5 3.5 0 0 0 0 5m5-5a3.5 3.5 0 0 1 0 5M7.75 7.75a6 6 0 0 0 0 8.5m8.5-8.5a6 6 0 0 1 0 8.5");
}

</style>
