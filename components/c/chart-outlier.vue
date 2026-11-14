<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p8u760b4u"/><path class="u3inh1bkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-outlier" /></template>
<style>
.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

.u3inh1bkt {
  d: path("m6.5 17l3-3.5l3.5 2l3.5-3.5l3.5 2M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
