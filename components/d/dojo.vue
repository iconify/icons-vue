<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qzcwbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dojo" /></template>
<style>
.i1qzcwbzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5C6 9.5 8 7 9 4h6c1 3 3 5.5 6.5 5.5Zm3.5 0V18m12-8.5V18M3.5 18h17v3h-17Z");
}

</style>
