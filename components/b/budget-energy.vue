<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yz_2k2d_s"/><path class="hrqunj3_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:budget-energy" /></template>
<style>
.hrqunj3_f {
  d: path("m13 10l-2.5 4.25h3L11 18.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz_2k2d_s {
  d: path("M4.25 18.5a9 9 0 1 1 15.5 0m-3.5-8.75l2-2");
}

</style>
