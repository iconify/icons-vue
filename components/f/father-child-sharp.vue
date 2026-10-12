<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="c7q9cg9gy"/><path class="vrswtybmz"/><circle class="eegh5rjsz"/><path class="uhx03_bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:father-child-sharp" /></template>
<style>
.c7q9cg9gy {
  cx: 7.5px;
  cy: 4.75px;
  r: 2px;
}

.eegh5rjsz {
  cx: 18.25px;
  cy: 12.25px;
  r: 1.5px;
}

.uhx03_bjx {
  d: path("M15.75 21.25v-2a2.5 2.5 0 0 1 5 0v2ZM12 15.75h3.75v3.5");
}

.vrswtybmz {
  d: path("M3 21.25v-6.5a4.5 4.5 0 0 1 9 0v6.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
