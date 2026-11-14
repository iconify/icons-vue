<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ou1o1l1de"/><path class="xlucx8b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fatty-acid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ou1o1l1de {
  d: path("m2.5 18l4-5l4 5l4-5V6");
}

.xlucx8b6j {
  d: path("M14 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3.25 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0-6.25V6.25M14.5 13l3.25 3.25");
}

</style>
