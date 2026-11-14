<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo4_2ab7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:activity-timeline" /></template>
<style>
.vo4_2ab7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-12v3m0 4v3m4-12h4.5m-17 7H8m8 7h3.5");
}

</style>
