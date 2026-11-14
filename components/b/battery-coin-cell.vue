<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sh7h1k-0d"/><path class="h0--x8cea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-coin-cell" /></template>
<style>
.h0--x8cea {
  d: path("M2.5 9v5.5a9.5 5.5 0 0 0 19 0V9M12 7v4m-2-2h4");
}

.sh7h1k-0d {
  d: path("M2.5 9a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
