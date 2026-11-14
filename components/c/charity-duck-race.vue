<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfhg-nbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-duck-race" /></template>
<style>
.dfhg-nbuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7.5l2.5 2h5a3.5 3.5 0 1 1 6.25-2l3.25.75l-3 1.5c1.5.75 2 1.75 2 2.75c0 2-2 2.5-4 2.5H8q-4.5 0-4.5-7.5ZM14 6h.01M3 18q2.25-.75 4.5 0t4.5 0t4.5 0t4.5 0M5 20.75q2.25-.75 4.5 0t4.5 0t4.5 0");
}

</style>
