<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="slsd0y7tu"/><path class="tmb5c1bwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-waste-sack" /></template>
<style>
.slsd0y7tu {
  d: path("m4 8l1 12q.1 1.5 1.5 1.5h11q1.4 0 1.5-1.5l1-12Zm2.5 0c0-4.5 3.5-4.5 3.5 0m4 0c0-4.5 3.5-4.5 3.5 0");
}

.tmb5c1bwt {
  d: path("M8.5 18.5c0-4 3-7 7-7c0 4-3 7-7 7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
