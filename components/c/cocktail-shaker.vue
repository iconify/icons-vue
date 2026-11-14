<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5d9tsfog"/><path class="mnk8qpckq"/><path class="xaz319zwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cocktail-shaker" /></template>
<style>
.a5d9tsfog {
  d: path("M11.5 2.5h1a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 12.5 5h-1a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 11.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mnk8qpckq {
  d: path("M9.54 5h4.92a1.5 1.5 0 0 1 1.405.973L16.25 7a1.48 1.48 0 0 1-1.386 2H9.136A1.48 1.48 0 0 1 7.75 7l.385-1.027A1.5 1.5 0 0 1 9.54 5");
}

.xaz319zwb {
  d: path("M8.482 9h7.036a1.75 1.75 0 0 1 1.736 1.967l-1.062 8.5A1.75 1.75 0 0 1 14.455 21h-4.91a1.75 1.75 0 0 1-1.737-1.533l-1.062-8.5A1.75 1.75 0 0 1 8.482 9M7.25 13h9.5");
}

</style>
