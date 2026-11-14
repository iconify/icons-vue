<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i3prevbvs"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookshelf-check" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.i3prevbvs {
  d: path("M13.3 20.5H2.5v-18h17v10.8m-17-1.8h17M6 5.5v6m2.75-6v6m3-5.5l2.75 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
