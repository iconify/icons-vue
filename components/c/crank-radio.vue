<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="quosksblg"/><path class="xc46riion"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crank-radio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.quosksblg {
  d: path("M7.5 8h9a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 16.5v-5A3.5 3.5 0 0 1 7.5 8M16 8l3.5-5.25");
}

.xc46riion {
  d: path("M7.5 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h6");
}

</style>
