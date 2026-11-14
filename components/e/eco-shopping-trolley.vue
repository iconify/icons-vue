<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g78bilb_k"/><path class="nvd351b7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-shopping-trolley" /></template>
<style>
.g78bilb_k {
  d: path("M2.5 4.5H5L7.5 16H18l2.5-7H6m1.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.nvd351b7d {
  d: path("M12.5 9c0-3.5 2-5.5 5.5-6c0 3.5-2 5.75-5.5 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
