<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="snm-237_c"/><path class="u7nvscbil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:licorice" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.snm-237_c {
  d: path("M16.25 12.75a4.25 4.25 0 0 0-8.5 0a6 6 0 0 0 12 0a7.75 7.75 0 0 0-15.5 0");
}

.u7nvscbil {
  d: path("M10.5 12.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
