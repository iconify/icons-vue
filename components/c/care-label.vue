<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vu98w7bpj"/><path class="e07hg-bcy"/><path class="bbi3-ab3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:care-label" /></template>
<style>
.bbi3-ab3a {
  d: path("M9.25 14q1.125-1.125 2.25 0t2.25 0c.5-.5.75-.5 1-.5");
}

.e07hg-bcy {
  d: path("M11 6.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0M6.75 11.5L9 17.75h6l2.25-6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vu98w7bpj {
  d: path("M9.207 2.5h5.586a2.63 2.63 0 0 1 1.993.917l1.582 1.846A2.63 2.63 0 0 1 19 6.971v11.404A2.625 2.625 0 0 1 16.375 21h-8.75A2.625 2.625 0 0 1 5 18.375V6.971a2.63 2.63 0 0 1 .632-1.708l1.582-1.846A2.63 2.63 0 0 1 9.207 2.5");
}

</style>
