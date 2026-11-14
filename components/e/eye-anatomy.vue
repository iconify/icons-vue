<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csof25-mz"/><path class="ceergvo1j"/><path class="i13_tbbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eye-anatomy" /></template>
<style>
.ceergvo1j {
  fill: currentColor;
  d: path("M4.5 8c1.5 1 2 2.5 2 4s-.5 3-2 4c-.75-1-1.25-2.5-1.25-4s.5-3 1.25-4");
}

.csof25-mz {
  d: path("M4.5 12a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i13_tbbbr {
  d: path("M19.5 12c.75.25 1.5 1 2 2.5");
}

</style>
