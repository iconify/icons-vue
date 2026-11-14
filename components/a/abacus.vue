<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0kbvhdzp"/><path class="nlyr-3b5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:abacus" /></template>
<style>
.i0kbvhdzp {
  d: path("M2.5 2.5h19v19h-19Zm6 4.5h13");
}

.nlyr-3b5a {
  d: path("M2.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3 5h13m0 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-16 5h3m6 0h10m-16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
