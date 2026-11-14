<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="usy_56bxf"/><path class="pvno39b9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:falling-rocks-sign" /></template>
<style>
.pvno39b9e {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm1.75 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.usy_56bxf {
  d: path("m12 3l9.5 17h-19ZM6.25 13.25L12.5 20");
}

</style>
