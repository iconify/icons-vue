<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ogisx2h0z"/><path class="c-xv40bvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-willow" /></template>
<style>
.c-xv40bvx {
  d: path("M4 20q7-7.5 13-13.5");
}

.ogisx2h0z {
  d: path("M4 20c2-9 7.5-15 16-16.5c-2.5 7-8 13-16 16.5Zm0 0l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
