<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yfgor35df"/><path class="zspe1_foj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:daisy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfgor35df {
  d: path("M16.75 11.25A2 2 0 0 1 14 14a2 2 0 0 1-4 0a2 2 0 0 1-2.75-2.75a2 2 0 0 1 0-4A2 2 0 0 1 10 4.5a2 2 0 0 1 4 0a2 2 0 0 1 2.75 2.75a2 2 0 0 1 0 4M12 16v5.5");
}

.zspe1_foj {
  d: path("M10 9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 11.25q4.5 0 6-3q-4-.5-6 3");
}

</style>
