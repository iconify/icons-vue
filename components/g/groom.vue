<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f306eb6uf"/><path class="hhoenug3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:groom" /></template>
<style>
.f306eb6uf {
  d: path("M8 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4 21.5c0-4 3.5-6.5 8-6.5s8 2.5 8 6.5");
}

.hhoenug3t {
  d: path("m12 17l-2.5-1.5v3Zm0 0l2.5-1.5v3Zm-6.5-.25L9 21.5m9.5-4.75L15 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
