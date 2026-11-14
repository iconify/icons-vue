<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n_bxed9ty"/><path class="bsluc0s4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-sold" /></template>
<style>
.bsluc0s4p {
  d: path("M16 6.25V3h2.5v5.5");
}

.n_bxed9ty {
  fill: currentColor;
  d: path("M3 10.5L12 3l9 7.5V21H3Zm3.25 4.25L10.5 19l7.25-7.25l-2.5-2.5L10.5 14l-1.75-1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
