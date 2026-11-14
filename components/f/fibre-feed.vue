<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r3qi-mblg"/><path class="dfgforb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fibre-feed" /></template>
<style>
.dfgforb6n {
  d: path("M9.5 12L12 9.5l2.5 2.5M8 17v4.5m8-4.5v4.5");
}

.r3qi-mblg {
  d: path("M7.5 14A4 4 0 0 1 8 6a5 5 0 0 1 9 1a3.5 3.5 0 0 1 0 7m-5 7.5v-12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
