<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="w0dy7ackv"/><path class="r34d66ayj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bmi-sharp" /></template>
<style>
.r34d66ayj {
  d: path("M8.75 21.25V17.5a3.25 3.25 0 0 1 6.5 0v3.75Zm-6-6.25a9.25 9.25 0 0 1 3.06-6.87m2.72-1.71a9.25 9.25 0 0 1 6.94 0m2.72 1.71A9.25 9.25 0 0 1 21.25 15");
}

.w0dy7ackv {
  cx: 12px;
  cy: 10.5px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
