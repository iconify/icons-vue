<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jpzm84ifn"/><path class="z9w5pkqbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrow-merge-right" /></template>
<style>
.jpzm84ifn {
  d: path("m3 6l7 6h11M3 18l7-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9w5pkqbx {
  d: path("M17.5 8.5L21 12l-3.5 3.5");
}

</style>
