<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xmo_79b-j"/><path class="p6rvgcb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doggy-bag" /></template>
<style>
.p6rvgcb9d {
  d: path("M9.5 14.5c0-1 1.5-2 2.5-.5c1-1.5 2.5-.5 2.5.5c0 1.5-2.5 3-2.5 3s-2.5-1.5-2.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmo_79b-j {
  d: path("M5 8h14l-1.5 12h-11Zm3.5 0V5.5A1.5 1.5 0 0 1 10 4h4a1.5 1.5 0 0 1 1.5 1.5V8");
}

</style>
