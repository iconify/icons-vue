<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1rth0svz"/><path class="pv3_j1d6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:density-layers" /></template>
<style>
.g1rth0svz {
  d: path("M5 3v16a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 19V3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pv3_j1d6x {
  d: path("M7.75 8Q10 6.5 12 8t4.25 0m-8.5 4.5Q10 11 12 12.5t4.25 0M7.75 17Q10 15.5 12 17t4.25 0");
}

</style>
