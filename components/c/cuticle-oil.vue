<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_u15bp5j"/><path class="ie6aejbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cuticle-oil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie6aejbji {
  d: path("M8.25 11V8.75a3.75 3.75 0 0 1 7.5 0V11q-3.75 1.5-7.5 0");
}

.q_u15bp5j {
  d: path("M5.5 13V8.75a6.5 6.5 0 0 1 13 0V13M12 15.25c1.5 1.5 3 2.75 3 3.75a3 3 0 0 1-6 0c0-1 1.5-2.25 3-3.75");
}

</style>
