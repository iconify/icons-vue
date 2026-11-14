<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oh_7r2dnp"/><path class="veju3ybsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fly-cast-loop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oh_7r2dnp {
  d: path("M3.5 21.5Q8 9 15 4.5m0 0c3-2 6.5-1.5 6.5 2s-5.5 4.5-8 4");
}

.veju3ybsv {
  d: path("M5.25 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
