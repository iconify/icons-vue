<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwrftd82o"/><path class="t1_ei-8gq"/><path class="dho8vjh4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cashback" /></template>
<style>
.dho8vjh4g {
  d: path("M14.25 10C14 9.25 13 8.75 12 8.75c-1.25 0-2.25.75-2.25 1.75c0 2.25 4.5.75 4.5 3c0 1-1 1.75-2.25 1.75c-1 0-2-.5-2.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwrftd82o {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.t1_ei-8gq {
  d: path("M18.5 5.5a9.25 9.25 0 1 1-13 0M3 5.5h2.5V8");
}

</style>
