<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3eae4byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-land" /></template>
<style>
.l3eae4byg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h19M4 9V6.5l2-2l2 2V9m-5.5 8Q7 12.5 10 9M6.5 21.5Q10 14 12 9m.5 12.5Q13.5 14 14 9m5 12.5Q17 14 16 9");
}

</style>
