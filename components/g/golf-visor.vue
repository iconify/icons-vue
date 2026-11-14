<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7_z5b_vs"/><path class="ag3e92bth"/><path class="kphmxuxop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-visor" /></template>
<style>
.ag3e92bth {
  d: path("M8 8v2.5a7 3.5 0 0 0 14 0V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kphmxuxop {
  d: path("M11 13.25c-3.5.5-7.25 2.25-8.25 4.25C7 19 14 18 18 13.75");
}

.r7_z5b_vs {
  d: path("M8 8a7 3.5 0 1 0 14 0A7 3.5 0 1 0 8 8");
}

</style>
