<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_b24ebdz"/><path class="krbfcis-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drama-masks" /></template>
<style>
.krbfcis-x {
  d: path("M4.75 10.5c1 1.5 2.5 1.5 3.5 0m7.5 6.5c1-1.5 2.5-1.5 3.5 0");
}

.o_b24ebdz {
  d: path("M2.5 4.5c2.5-1 5.5-1 8 0v5c0 3-1.5 5-4 5s-4-2-4-5Zm11 5c2.5-1 5.5-1 8 0v5c0 3-1.5 5-4 5s-4-2-4-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
