<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb078_k3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adjacency-diagram" /></template>
<style>
.eb078_k3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H8v5.5H2.5ZM16 3h5.5v5.5H16ZM9.25 15.5h5.5V21h-5.5ZM8 5.75h8M6.5 8.5l4 7m7-7l-4 7");
}

</style>
