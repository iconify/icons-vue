<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rec4hebat"/><path class="ovvicntxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-energy-centre" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ovvicntxu {
  d: path("M6 21.5V17h3.5v4.5");
}

.rec4hebat {
  d: path("M2.5 21.5V12l5-3.5V12l5-3.5V12h1V3.5H16V12h2.75V6h2.75v15.5Z");
}

</style>
