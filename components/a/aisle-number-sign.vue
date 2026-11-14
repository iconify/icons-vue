<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfq8yoh9v"/><path class="d6m66vbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aisle-number-sign" /></template>
<style>
.d6m66vbww {
  d: path("M14.75 9h-4.5l-.5 3.75c.75-.5 1.5-.75 2.5-.75c1.75 0 3 1.25 3 3s-1.5 3-3.25 3c-1.25 0-2.25-.5-2.75-1.5M5.5 9h.01M18.5 9h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfq8yoh9v {
  d: path("M2.5 2.5h19M7 2.5V6m10-3.5V6M6 6h12a3.5 3.5 0 0 1 3.5 3.5v8A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-8A3.5 3.5 0 0 1 6 6");
}

</style>
