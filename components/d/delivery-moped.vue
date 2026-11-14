<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uu25ibbvi"/><path class="gkvybgbxk"/><path class="o3z-nt8xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-moped" /></template>
<style>
.gkvybgbxk {
  d: path("M5.5 17.5H12L14 8h4.5");
}

.o3z-nt8xq {
  d: path("M6 6h7v5H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uu25ibbvi {
  d: path("M2.5 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
