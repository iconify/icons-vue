<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olfenrkki"/><path class="d5z8kbc0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coast" /></template>
<style>
.d5z8kbc0g {
  d: path("M11.5 11q2.25-1.5 4.5 0t4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olfenrkki {
  d: path("M2.5 2.5H9c2.5 1.5 2.5 4 .5 5.5c-3 2-3 5 .5 6.5c3 1 5.5 2.5 5.5 7h-13Zm12 3q1.75-1.5 3.5 0t3.5 0");
}

</style>
