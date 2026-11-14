<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yv0r5iqto"/><path class="d2vbfwjlf"/><path class="o56nglbsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-type-boolean" /></template>
<style>
.d2vbfwjlf {
  d: path("M8.75 9.25h6.5A2.75 2.75 0 0 1 18 12a2.75 2.75 0 0 1-2.75 2.75h-6.5A2.75 2.75 0 0 1 6 12a2.75 2.75 0 0 1 2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o56nglbsg {
  fill: currentColor;
  d: path("M14 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.yv0r5iqto {
  d: path("M10.375 2.5h3.25a7.875 7.875 0 0 1 7.875 7.875v3.25a7.875 7.875 0 0 1-7.875 7.875h-3.25A7.875 7.875 0 0 1 2.5 13.625v-3.25A7.875 7.875 0 0 1 10.375 2.5");
}

</style>
