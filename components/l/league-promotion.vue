<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlah1wp5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:league-promotion" /></template>
<style>
.vlah1wp5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h10v5.5a5 5 0 0 1-10 0Zm0 2H4.5a2 2 0 0 0 0 4H6m10-4h1.5a2 2 0 0 1 0 4H16m-5 4.5V19m-2.5 0h4.6m4.9 2v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
