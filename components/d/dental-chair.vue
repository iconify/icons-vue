<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mj5l8cb-a"/><path class="tkp0zbbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-chair" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mj5l8cb-a {
  d: path("M4.375 2.5h1.75A1.375 1.375 0 0 1 7.5 3.875A1.375 1.375 0 0 1 6.125 5.25h-1.75A1.375 1.375 0 0 1 3 3.875A1.375 1.375 0 0 1 4.375 2.5M5.75 5.25L9 13.5h8l3.5 4.5");
}

.tkp0zbbwc {
  d: path("M7.75 10.25h6.75v3.25m0 0V21m-4 0h8");
}

</style>
