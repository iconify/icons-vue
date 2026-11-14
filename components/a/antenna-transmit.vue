<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfy0g7jdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna-transmit" /></template>
<style>
.mfy0g7jdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2v5.5M8 21l4-6.5l4 6.5m-.641-17.359a4.75 4.75 0 0 1 0 6.718m-6.718 0a4.75 4.75 0 0 1 0-6.718M18.928 3a8 8 0 0 1 0 8M5.072 11a8 8 0 0 1 0-8");
}

</style>
