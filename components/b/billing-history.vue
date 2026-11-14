<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lknw1x09y"/><path class="h2c5kvbda"/><path class="dfka36boz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:billing-history" /></template>
<style>
.dfka36boz {
  d: path("m17.25 14.5l-2 2l2 2");
}

.h2c5kvbda {
  d: path("m12.468 17.646l-.218-.146L10 19l-2.5-1.5V5.25H19v7.1m-8.5-3.1H16m-5.5 4h3m1.75 3.25h3.5a2.5 2.5 0 0 1 0 5H16");
}

.lknw1x09y {
  d: path("M4.5 17V4.5a2 2 0 0 1 2-2h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
