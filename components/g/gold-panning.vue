<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbsiky0ms"/><path class="zjb_lcpqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gold-panning" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbsiky0ms {
  d: path("m2.5 4.5l4 8l11 2l4-6.5M3 19q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

.zjb_lcpqv {
  d: path("m10 8.5l3.5-1l1 2.5l-4 .75Z");
}

</style>
