<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8bfp9qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-pile" /></template>
<style>
.bh8bfp9qd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.25a5.75 5.75 0 0 1 8-4a5.75 5.75 0 0 1-8 4m11-4a5.75 5.75 0 0 1 8 4a5.75 5.75 0 0 1-8-4m-6-5a5.75 5.75 0 0 1 9 0a5.75 5.75 0 0 1-9 0m-4.5 12h18");
}

</style>
