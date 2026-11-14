<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frls69boe"/><path class="kfxqqfhsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baggage-tractor" /></template>
<style>
.frls69boe {
  d: path("M13.5 15V9.5h3l1-4H20l1.5 4V15Zm-11 0h11M5.25 8h4A1.75 1.75 0 0 1 11 9.75v3.5A1.75 1.75 0 0 1 9.25 15h-4a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 5.25 8m.5 0V5.5h3V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfxqqfhsv {
  d: path("M4.5 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
