<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p6ja0gd_l"/><path class="k0j7chc5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floor-plane" /></template>
<style>
.k0j7chc5n {
  d: path("M9.5 6h5v9h-5Zm0 3h5");
}

.p6ja0gd_l {
  d: path("M9.5 12h-3l-4 6h15l4-6h-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
