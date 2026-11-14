<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4ph18stj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grass-height-ruler" /></template>
<style>
.c4ph18stj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h6v19H9ZM9 7h3.25M9 11h2.25M9 15h3.25M2.5 21.5h19M4 21.5q0-3-1.5-5m3.75 5q0-2.5-.75-4.5M20 21.5q0-3 1.5-5m-3.75 5q0-2.5.75-4.5");
}

</style>
