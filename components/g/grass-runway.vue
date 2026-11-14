<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ok8mbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grass-runway" /></template>
<style>
.f6ok8mbsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v8h-19Zm3 4H8m2.75 0h2.5M16 8h2.5m-16 12.5h19m-17 0q0-3-2-4.5m2 4.5q0-3 2-4.5m5.5 4.5q0-3-2-4.5m2 4.5q0-3 2-4.5m5.5 4.5q0-3-2-4.5m2 4.5q0-3 2-4.5");
}

</style>
