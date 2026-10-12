<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ktlq2iblr"/><path class="cl7qweb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:headband-sharp" /></template>
<style>
.cl7qweb_u {
  d: path("M11.48 7.2L9.52 6.05L9 5.75v3.5l.52-.3l1.96-1.15l.52-.3zm1.04 0l1.96-1.15l.52-.3v3.5l-.52-.3l-1.96-1.15l-.52-.3z");
}

.ktlq2iblr {
  d: path("M3.5 17a8.5 8.5 0 0 1 17 0a1.25 1.25 0 0 1-2.5 0a6 6 0 0 0-12 0a1.25 1.25 0 0 1-2.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
