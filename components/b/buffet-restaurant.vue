<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wn6-bq65w"/><path class="oyybhab8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:buffet-restaurant" /></template>
<style>
.oyybhab8w {
  d: path("M10.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-5 10L7 20h10l1.5-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn6-bq65w {
  d: path("M3.5 16a8.5 8.5 0 0 1 17 0m-18 0h19");
}

</style>
