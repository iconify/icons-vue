<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="qa2tr1beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doughnut" /></template>
<style>
.qa2tr1beq {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm2.5-6.75l1 1.25m5.765 2.939l-.88 1.337m-1.013 6.391l-1.544-.424m-6.391 1.012l-.074-1.599M5.426 10.39l1.498-.565");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
