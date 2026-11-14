<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0pyvwjop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bridge-pontoon" /></template>
<style>
.m0pyvwjop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19m-19 0V10A2.25 2.25 0 0 0 7 10V6.5m2.75 0V10a2.25 2.25 0 0 0 4.5 0V6.5m2.75 0V10a2.25 2.25 0 0 0 4.5 0V6.5m-19 9.25q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
