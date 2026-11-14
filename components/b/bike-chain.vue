<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8w7rkkwg"/><path class="bi23adoxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-chain" /></template>
<style>
.bi23adoxa {
  d: path("M11.75 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-5.5 0h.01");
}

.c8w7rkkwg {
  d: path("m5 8.75l8.25-2.5a6 6 0 1 1 0 11.5L5 15.25a3.5 3.5 0 0 1 0-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
