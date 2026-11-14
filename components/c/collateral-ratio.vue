<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sao3-lbgz"/><path class="snmk61b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:collateral-ratio" /></template>
<style>
.sao3-lbgz {
  d: path("M3.5 6h17M12 3.5v17m-3.5 0h7M5 6v3.5m-3 4h6a3 2.5 0 0 1-6 0ZM19 6v7.5m-3 0h6a3 2.5 0 0 1-6 0Z");
}

.snmk61b_t {
  d: path("M3 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
