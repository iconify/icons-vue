<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dc4e98b_m"/><path class="cxyl9s35b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biathlete" /></template>
<style>
.cxyl9s35b {
  d: path("M2.5 20.5h17q2 0 2-2M5 12.5l6-6");
}

.dc4e98b_m {
  d: path("M13.75 5.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m.25 4.5L9.5 14m0 0l3.5 3l-1 3.5M9.5 14L7 20.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
