<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6nu4lk3f"/><path class="rswa1_mlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-for-sale" /></template>
<style>
.e6nu4lk3f {
  d: path("M3.945 9.713L10.32 4.4a2.625 2.625 0 0 1 3.36 0l6.375 5.313A2.63 2.63 0 0 1 21 11.729v6.646A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-6.646a2.63 2.63 0 0 1 .945-2.016");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rswa1_mlw {
  d: path("M14.25 12.75C14 11.9 13.15 11.5 12 11.5c-1.4 0-2.25.7-2.25 1.75c0 2.1 4.5 1.2 4.5 4c0 1-.95 1.75-2.25 1.75c-1.2 0-2.05-.5-2.25-1.25M12 10v1.5m0 7.5v1.5");
}

</style>
