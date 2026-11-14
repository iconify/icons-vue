<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7latrbdk"/><path class="r2-eo_i_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:help-triangle" /></template>
<style>
.m7latrbdk {
  d: path("m12 3l9.5 16.75h-19Z");
}

.r2-eo_i_z {
  d: path("M10.5 11.75c0-.85.7-1.5 1.5-1.5s1.5.65 1.5 1.5c0 1.15-1.5 1.35-1.5 2.5M12 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
