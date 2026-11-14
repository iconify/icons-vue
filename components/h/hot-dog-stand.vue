<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfn7x-w3t"/><path class="taumxbiob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-dog-stand" /></template>
<style>
.bfn7x-w3t {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M3.5 16h17M5 16v5.5M19 16v5.5m-12.5-10h11A1.5 1.5 0 0 1 19 13a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 13a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.taumxbiob {
  d: path("M6.5 13v1a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2v-1");
}

</style>
