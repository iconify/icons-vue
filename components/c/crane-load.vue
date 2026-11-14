<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h404vvw4n"/><path class="ggts-h53t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crane-load" /></template>
<style>
.ggts-h53t {
  d: path("m7 15l5-4.5l5 4.5m-9.875 0h9.75a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875v-1.25A2.625 2.625 0 0 1 7.125 15");
}

.h404vvw4n {
  d: path("M14.5 2.5V8a2.5 2.5 0 0 1-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
