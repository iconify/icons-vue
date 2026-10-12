<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nciaxcb6w"/><path class="skh6m6vww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-down-square-sharp" /></template>
<style>
.nciaxcb6w {
  d: path("M3.25 3.25h17.5v17.5H3.25z");
}

.skh6m6vww {
  d: path("M12 7.5v8.75m3.75-3.75L12 16.25L8.25 12.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
