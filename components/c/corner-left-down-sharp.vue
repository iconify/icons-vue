<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qrtm-bc2v"/><path class="g7r2n3-ke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-left-down-sharp" /></template>
<style>
.g7r2n3-ke {
  d: path("m13 15.5l-3.75 3.75L5.5 15.5");
}

.qrtm-bc2v {
  d: path("M19.75 4.25H9.25v15");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
