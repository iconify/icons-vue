<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7latrbdk"/><path class="gv35aobpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:high-voltage" /></template>
<style>
.gv35aobpj {
  d: path("M12.75 8L9 13.75h2.75l-.5 3.5L15 12h-2.75Z");
}

.m7latrbdk {
  d: path("m12 3l9.5 16.75h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
