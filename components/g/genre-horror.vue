<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpoefdc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-horror" /></template>
<style>
.hpoefdc2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5V10a7 7 0 0 1 14 0v10.5q-1.75-2-3.5 0t-3.5 0t-3.5 0t-3.5 0Zm4.5-10h.01m4.99 0h.01");
}

</style>
