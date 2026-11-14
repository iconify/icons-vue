<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="koa6vbczn"/><path class="q49fcz69s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-shop" /></template>
<style>
.koa6vbczn {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v1.5M4.5 11v9.5H12");
}

.q49fcz69s {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m4.75 1.5l4.25-5.25c1-1.25.25-1.5-1.25-1.5S16 15.5 17 16.75L21.25 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
