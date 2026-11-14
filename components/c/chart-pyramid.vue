<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2enuber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-pyramid" /></template>
<style>
.tm2enuber {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.548 5.932l6.597 12.501A1.75 1.75 0 0 1 18.598 21H5.402a1.75 1.75 0 0 1-1.547-2.567l6.597-12.501a1.75 1.75 0 0 1 3.096 0M8.75 9h6.5m-9.5 6h12.5");
}

</style>
