<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pqqi06bzb"/><path class="jknmb9xkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cylinder-sharp" /></template>
<style>
.jknmb9xkh {
  d: path("M3.5 6a8.5 3.25 0 1 0 17 0a8.5 3.25 0 1 0-17 0Z");
}

.pqqi06bzb {
  d: path("M3.5 6v12a8.5 3.25 0 0 0 17 0V6a8.5 3.25 0 0 1-17 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
