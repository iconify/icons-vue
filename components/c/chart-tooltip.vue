<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kpcwc9npf"/><path class="sbphn8l1y"/><path class="g9g-rcbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-tooltip" /></template>
<style>
.g9g-rcbiq {
  d: path("M11.5 2.5h7a2 2 0 0 1 2 2V6a2 2 0 0 1-2 2h-2L15 10l-1.5-2h-2a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2m1 2.75h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpcwc9npf {
  d: path("M2.5 20L7 15.5l4 2l4-4.5l6.5 3.5");
}

.sbphn8l1y {
  fill: currentColor;
  d: path("M13.5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
