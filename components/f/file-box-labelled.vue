<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cq8jo2bli"/><path class="flcescchj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-box-labelled" /></template>
<style>
.cq8jo2bli {
  d: path("M4 8v11a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8M4 8l2.5-4h11L20 8Z");
}

.flcescchj {
  d: path("M10.75 12h2.5A1.75 1.75 0 0 1 15 13.75a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 13.75A1.75 1.75 0 0 1 10.75 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
