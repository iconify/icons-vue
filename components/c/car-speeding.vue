<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gdyzmbc6q"/><path class="ssjip1bkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-speeding" /></template>
<style>
.gdyzmbc6q {
  d: path("M9.5 15.5H8V12l2.5-1.5L13 7h4.5l2.5 3.5l1.5.75v4.25h-1m-7 0h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ssjip1bkz {
  d: path("M9.5 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M2.5 9H7m-4.5 3H5m-2.5 3H5");
}

</style>
