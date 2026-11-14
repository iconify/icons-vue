<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zrux4cf_s"/><path class="d33dmjb-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cola-with-lemon" /></template>
<style>
.d33dmjb-e {
  d: path("M8.5 12.25H12v3.5H8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrux4cf_s {
  d: path("M4 6h12.5l-2 15H6Zm.25 3.5h12M14 6a3.5 3.5 0 0 1 7 0Z");
}

</style>
