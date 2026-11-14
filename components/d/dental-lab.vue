<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1uk5_d-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-lab" /></template>
<style>
.h1uk5_d-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.205 15H5C3.5 9 5.5 4 9 4.25c1.5.15 2 .75 3 .75s1.5-.6 3-.75c2.68-.191 4.481 2.696 4.504 6.754M18.25 14.5a2.5 2.5 0 1 0 3.25 3.25m-6.75 3.5l3-3");
}

</style>
