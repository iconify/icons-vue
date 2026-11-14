<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xeuvs5bpm"/><path class="uwkevkpjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:command-post" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwkevkpjz {
  d: path("m9.5 20.5l2.5-5l2.5 5");
}

.xeuvs5bpm {
  d: path("M2.5 20.5L12 9l9.5 11.5ZM12 9V3l4.5 1.5L12 6");
}

</style>
