<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkoirnb0d"/><path class="oncki7f2g"/><path class="c6bhbubal"/><path class="y3g1wztdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coal-plant-outline-thin" /></template>
<style>
.c6bhbubal {
  d: path("M7.5 12a2.5 2.5 0 0 1 0 -5");
}

.fkoirnb0d {
  d: path("M5 20v-8h5v8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oncki7f2g {
  d: path("M13 20v-5h5v5Z");
}

.y3g1wztdf {
  d: path("M7.5 2a2.5 2.5 0 0 1 0 5");
}

</style>
