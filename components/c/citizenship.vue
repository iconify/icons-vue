<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b168u88ao"/><path class="w_g7v8g7d"/><path class="vv8ix5bke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:citizenship" /></template>
<style>
.b168u88ao {
  d: path("m4.38 4.487l12.874-1.809l2.366 16.835l-12.874 1.809Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vv8ix5bke {
  d: path("M10.25 10.5a1.75 3.75 0 1 0 3.5 0a1.75 3.75 0 1 0-3.5 0Zm.005 7.047l4.951-.696");
}

.w_g7v8g7d {
  d: path("M8.041 10.515a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

</style>
