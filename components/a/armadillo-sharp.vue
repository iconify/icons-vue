<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kqmfg7bsx"/><path class="y3yqndb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:armadillo-sharp" /></template>
<style>
.kqmfg7bsx {
  d: path("M8.5 16.5c0-5.5 1.75-9.25 4.5-9.25s4.5 3.75 4.5 9.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3yqndb1p {
  d: path("M8.75 12.5H6.5l-2 2l-1.25 1.25l-.75.75h6Zm-1.85.25l-.65-2.5m5.5.75v5.5m2.5-5.5v5.5M17.4 15l2.525 1.263l1.325 1.987m-11-1.75v2.75m5.5-2.75v2.75");
}

</style>
