<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjj3s4yij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemistry" /></template>
<style>
.vjj3s4yij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5H10v6l-5.5 10Q3.5 21 6 21h12q2.5 0 1.5-2.5L14 8.5v-6h1.5m-8.75 12h10.5");
}

</style>
