<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eoeoqudwa"/><path class="h15vce0kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-merge-left" /></template>
<style>
.eoeoqudwa {
  d: path("M21 5h-2.5c-4 0-4.5 7-8.5 7H3.5M21 19h-2.5c-4 0-4.5-7-8.5-7");
}

.h15vce0kf {
  d: path("M7 8.5L3.5 12L7 15.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
