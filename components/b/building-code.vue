<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o4-7vsbpi"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-code" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.o4-7vsbpi {
  d: path("M14.3 21.5H4.5v-19h15v10.8m0 7.9v.3h-.3M8 2.5v19M11 7h5m-5 4h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
