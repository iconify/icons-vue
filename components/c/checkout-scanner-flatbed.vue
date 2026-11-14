<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qjd64fbhh"/><path class="x_39kgb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-scanner-flatbed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qjd64fbhh {
  d: path("m3.873 17.426l2.133-4A1.75 1.75 0 0 1 7.55 12.5h11.033a1.75 1.75 0 0 1 1.544 2.574l-2.133 4A1.75 1.75 0 0 1 16.45 20H5.417a1.75 1.75 0 0 1-1.544-2.574");
}

.x_39kgb_s {
  d: path("M11.25 5h3A1.75 1.75 0 0 1 16 6.75v4a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 11.25 5m1.5 0v3M7 16.25h9.5");
}

</style>
