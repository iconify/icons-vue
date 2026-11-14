<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb74eqbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:days-on-market" /></template>
<style>
.jb74eqbnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h17v17h-17Zm4.5-2v4m8-4v4M3.5 9h17M7 12v6m3-6v6m3-6v6m3-6v6m-10.5-.5l12-5");
}

</style>
