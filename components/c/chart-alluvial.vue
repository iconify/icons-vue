<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lma7teuyb"/><path class="o1yco9hui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-alluvial" /></template>
<style>
.lma7teuyb {
  fill: currentColor;
  d: path("M2.5 2.5H5v9H2.5Zm0 11.5H5v7.5H2.5ZM19 8.5h2.5v7H19Zm0 9.5h2.5v3.5H19Z");
}

.o1yco9hui {
  d: path("M5 3.5c7 0 7 6 14 6v5C12 14.5 12 9 5 9Zm0 14c7 0 7 2.25 14 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
