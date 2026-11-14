<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rylwk1z8m"/><path class="h_0vejb0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drop-ship-order" /></template>
<style>
.h_0vejb0e {
  d: path("m12 15.5l4.75-4.75l4.75 4.75v6H12Z");
}

.rylwk1z8m {
  d: path("M2.5 2.5h6v6h-6Zm6 6l5.25 5.25m-3 0h3v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
