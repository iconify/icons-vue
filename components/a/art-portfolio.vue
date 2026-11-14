<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ry9sqrbnp"/><path class="tudd506gt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-portfolio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ry9sqrbnp {
  d: path("M5.125 8.5h13.75a2.625 2.625 0 0 1 2.625 2.625v6.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 17.875v-6.75A2.625 2.625 0 0 1 5.125 8.5M8 8.5v-2a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2");
}

.tudd506gt {
  d: path("M10.5 8.5V12h3V8.5");
}

</style>
