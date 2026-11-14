<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trh2ghbkw"/><path class="nao-8bmfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leave-request" /></template>
<style>
.nao-8bmfv {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h3.5M10 13c0-1 1-1.5 2-1.5s2 .5 2 1.5c0 1.5-2 1.5-2 3m0 2.25h.01");
}

.trh2ghbkw {
  d: path("M6.5 2.5h11v19h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
