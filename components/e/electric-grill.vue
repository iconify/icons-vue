<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pft03ybna"/><path class="xty35prln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-grill" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pft03ybna {
  d: path("M8.505 4.5h8.558a2.625 2.625 0 0 1 2.533 3.316l-1.568 5.75a2.625 2.625 0 0 1-2.533 1.934H6.937a2.625 2.625 0 0 1-2.533-3.316l1.568-5.75A2.625 2.625 0 0 1 8.505 4.5");
}

.xty35prln {
  d: path("M15 15.5v2a2 2 0 0 0 2 2h4.5M9.5 7.25L8 12.75m5-5.5l-1.5 5.5m5-5.5l-1.5 5.5");
}

</style>
