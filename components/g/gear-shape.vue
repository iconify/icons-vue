<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hwywxlbhe"/><path class="bnjnom5xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gear-shape" /></template>
<style>
.bnjnom5xi {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.hwywxlbhe {
  d: path("m9.5 5.5l.75-2.75h3.5l.75 2.75l2 1.25L19.25 6L21 8.75l-2 2v2.5l2 2L19.25 18l-2.75-.75l-2 1.25l-.75 2.75h-3.5L9.5 18.5l-2-1.25l-2.75.75L3 15.25l2-2v-2.5l-2-2L4.75 6l2.75.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
