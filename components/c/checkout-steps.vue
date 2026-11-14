<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fy8wmcbpp"/><path class="olojcv4zz"/><path class="gtjxdsbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-steps" /></template>
<style>
.fy8wmcbpp {
  d: path("M6.5 12h3.25m4.5 0h3.25");
}

.gtjxdsbko {
  d: path("M9.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.75 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olojcv4zz {
  fill: currentColor;
  d: path("M2 12a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 2 12");
}

</style>
