<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdcdkbc0u"/><path class="tudd506gt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-portfolio" /></template>
<style>
.tudd506gt {
  d: path("M10.5 8.5V12h3V8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdcdkbc0u {
  d: path("M2.5 8.5h19v12h-19Zm5.5 0v-2a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2");
}

</style>
