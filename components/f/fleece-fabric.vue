<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lv_du8bun"/><path class="fhpegdbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fleece-fabric" /></template>
<style>
.fhpegdbbf {
  d: path("M14.5 3.5q0 6.5 6.5 6.5");
}

.lv_du8bun {
  d: path("M3 3.5h11.5L21 10v9q-2.25 3-4.5 0q-2.25 3-4.5 0q-2.25 3-4.5 0q-2.25 3-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
