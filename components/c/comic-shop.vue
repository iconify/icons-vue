<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="koa6vbczn"/><path class="k2u2jdblt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:comic-shop" /></template>
<style>
.k2u2jdblt {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m7.75-5.25c2 0 3.5 1 3.5 2.5s-1.5 2.5-3.5 2.5l-3 1.5l.75-2c-.75-.5-1.25-1.25-1.25-2c0-1.5 1.5-2.5 3.5-2.5Z");
}

.koa6vbczn {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v1.5M4.5 11v9.5H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
