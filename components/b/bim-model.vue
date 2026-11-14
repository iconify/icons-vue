<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n70g8xb1k"/><path class="ue90-3xlj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bim-model" /></template>
<style>
.n70g8xb1k {
  d: path("M3 9h12v12H3Z");
}

.ue90-3xlj {
  d: path("m3 9l6-6h12v12l-6 6m6-18l-6 6M9 5v2.5m0 3V13m2 2h2.5m3 0H19M7.75 16.25l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
