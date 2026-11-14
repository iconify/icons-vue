<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-xti72pq"/><path class="myeutd6ys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altcoin-season" /></template>
<style>
.e-xti72pq {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4m-13 3h18");
}

.myeutd6ys {
  d: path("m7 18l3.5-3.5l3 1.5l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
