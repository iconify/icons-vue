<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lzrm5_ont"/><path class="yn85jj7ld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkout-zone" /></template>
<style>
.lzrm5_ont {
  d: path("M2.5 6.5v-2a2 2 0 0 1 2-2h2m11 0h2a2 2 0 0 1 2 2v2m0 11v2a2 2 0 0 1-2 2h-2m-11 0h-2a2 2 0 0 1-2-2v-2m8-15h3m-3 19h3m-11-11v3m19-3v3M6.5 6H11v3H6.5Zm2.25 3v1.5m-1.5 0h9.5L18 14H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yn85jj7ld {
  d: path("M6 14h12v4H6Zm7.75-1.75h.01M8.5 16h3");
}

</style>
