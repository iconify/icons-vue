<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nd_sn0bvq"/><path class="aef6mxlsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cupcake-duotone-round" /></template>
<style>
.aef6mxlsd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 14h14l-1 5c-.24 1.18-.9 2-2 2H8c-1.1 0-1.76-.82-2-2zm5 0v7m4-7v7m5-7c2.998-1.706 2.356-6.202-1-7c-.115-2.5-2.74-4.075-5-3a5 5 0 0 0-8 4c-2.567 1.176-2.567 4.824 0 6");
}

.ft5dv1b6b {
  fill: none;
}

.nd_sn0bvq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 15H5a1 1 0 0 1-.417-.091a4.3 4.3 0 0 1-2.329-2.655a4.3 4.3 0 0 1 .448-3.507A4.16 4.16 0 0 1 4.03 7.391a6 6 0 0 1 9.092-4.515a4.507 4.507 0 0 1 5.789 3.364c2.069.813 3.268 2.951 2.966 5.143a4.7 4.7 0 0 1-1.183 2.534c-.347.378-.752.7-1.2.952A1 1 0 0 1 19 15");
}

</style>
