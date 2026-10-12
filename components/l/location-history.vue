<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chc1rqbnv"/><circle class="d3jhe5bxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:location-history" /></template>
<style>
.chc1rqbnv {
  d: path("M12 21.25c-.35 0-.7-.13-.95-.38C8.1 18.1 4.75 14.4 4.75 10a7.25 7.25 0 0 1 14.5 0c0 4.4-3.35 8.1-6.3 10.87c-.25.25-.6.38-.95.38");
}

.d3jhe5bxu {
  cx: 12px;
  cy: 10px;
  r: 2.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
