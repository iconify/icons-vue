<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z_ludw-qx"/><circle class="shutjyb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anniversary-heart-sharp" /></template>
<style>
.shutjyb7t {
  cx: 12px;
  cy: 10.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_ludw-qx {
  d: path("m12 18.9l-5.95-5.95C4.78 11.72 3.5 10.23 3.5 8.28c0-2.59 2.09-4.68 4.68-4.68h2.107L12 5.3l1.713-1.7h2.107c2.59 0 4.68 2.09 4.68 4.68c0 1.95-1.27 3.44-2.55 4.67Z");
}

</style>
