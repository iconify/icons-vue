<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebmh19b5e"/><path class="gimc6tbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:driveway" /></template>
<style>
.ebmh19b5e {
  d: path("M2.5 17.5V14a1 1 0 0 1 1-1h2L8 10.5h5.5l3 2.5h4a1 1 0 0 1 1 1v3.5Z");
}

.gimc6tbdd {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-12.5 2h19M15.483 5.055l1.75-1.616a1.5 1.5 0 0 1 2.034 0l1.75 1.616a1.5 1.5 0 0 1 .483 1.102V7A1.5 1.5 0 0 1 20 8.5h-3.5A1.5 1.5 0 0 1 15 7v-.843a1.5 1.5 0 0 1 .483-1.102M18.25 8.5V6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
