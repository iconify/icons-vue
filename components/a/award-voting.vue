<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u10fdgbiq"/><path class="lyqk4dcxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:award-voting" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyqk4dcxz {
  d: path("m9.75 7l1.5 1.5l3-3");
}

.u10fdgbiq {
  d: path("M6.5 11h11a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18v-3.5A3.5 3.5 0 0 1 6.5 11m.5 0V3.5a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V11");
}

</style>
