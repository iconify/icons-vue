<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k-o90795g"/><path class="jzmhj5bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bougainvillea" /></template>
<style>
.jzmhj5bml {
  d: path("M18 4a2 2 0 0 1 0 4a2 2 0 0 1-4 0a2 2 0 0 1 0-4a2 2 0 0 1 4 0ZM9 9a2 2 0 0 1 0 4a2 2 0 0 1-4 0a2 2 0 0 1 0-4a2 2 0 0 1 4 0Zm3.5 7c3-1 6 .5 7 3c-3 .5-6-.5-7-3ZM16 6h.01M7 11h.01");
}

.k-o90795g {
  d: path("M9 21.5c0-5 7-6 7-11.5m-6 8.5L7 15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
