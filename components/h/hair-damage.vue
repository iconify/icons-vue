<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ubmx4gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-damage" /></template>
<style>
.e-ubmx4gv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.5c2 4 2 8.5 1 12m0 0c-1 2.5-3.5 5-5.5 7m5.5-7c1 2.5 3.5 5 5.5 7");
}

</style>
