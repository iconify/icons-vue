<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m03l82ghx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:asic-miner" /></template>
<style>
.m03l82ghx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5h10v10H7Zm3-3v3m4-3v3M4 9h3m-3 3h3m10-3h3m-3 3h3m-10 3.5v5m4-5v5m-11.5 0h19");
}

</style>
