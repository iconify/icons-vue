<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cc52jybxo"/><path class="c4s53xbcf"/><circle class="d4da7x21x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gan-pair-sharp" /></template>
<style>
.c4s53xbcf {
  d: path("m7 4.5l.3 2.2l2.2.3l-2.2.3L7 9.5l-.3-2.2L4.5 7l2.2-.3zm7 .25h4.75v4.5M17 7.5l1.75 1.75L20.5 7.5M10 19.25H5.25v-4.5M3.5 16.5l1.75-1.75L7 16.5");
}

.cc52jybxo {
  d: path("M2.75 2.75h8.5v8.5h-8.5z");
}

.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
