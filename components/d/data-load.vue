<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbs947byy"/><path class="hppncrbsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-load" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppncrbsz {
  d: path("M4 14c0 1.4 3.6 2.5 8 2.5s8-1.1 8-2.5M12 2.5V9M8.75 5.75L12 9l3.25-3.25");
}

.lbs947byy {
  d: path("M4 14c0-1.4 3.6-2.5 8-2.5s8 1.1 8 2.5v5c0 1.4-3.6 2.5-8 2.5S4 20.4 4 19Z");
}

</style>
