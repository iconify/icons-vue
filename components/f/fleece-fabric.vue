<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lv_du8bun"/><path class="fhpegdbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fleece-fabric" /></template>
<style>
.fhpegdbbf {
  d: path("M14.5 3.5q0 6.5 6.5 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lv_du8bun {
  d: path("M3 3.5h11.5L21 10v9q-2.25 3-4.5 0q-2.25 3-4.5 0q-2.25 3-4.5 0q-2.25 3-4.5 0Z");
}

</style>
