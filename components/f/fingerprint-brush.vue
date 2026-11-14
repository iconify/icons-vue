<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbtlzobnp"/><path class="howta4bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fingerprint-brush" /></template>
<style>
.howta4bbh {
  d: path("M2.5 16.5v3.25a5.5 1.75 0 0 0 11 0V16.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbtlzobnp {
  d: path("m16 5.5l-4.25 2.75a2.5 2.5 0 0 0 3.5 3.5L18 7.5Zm1 1l4-4m-18.5 14a5.5 1.75 0 1 0 11 0a5.5 1.75 0 1 0-11 0Z");
}

</style>
