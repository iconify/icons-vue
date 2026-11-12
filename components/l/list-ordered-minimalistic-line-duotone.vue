<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ll_t976_m"/><path class="bp9f0acyy"/><path class="i1rjgtlrr"/><path class="iw9omoj8x"/><path class="j6st1829s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-ordered-minimalistic-line-duotone" /></template>
<style>
.bp9f0acyy {
  d: path("M20 11L12 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i1rjgtlrr {
  d: path("M20 6L12 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw9omoj8x {
  stroke-linejoin: round;
  d: path("M5.13477 6.5136L7.06207 5V9");
}

.j6st1829s {
  stroke-linejoin: round;
  d: path("M5.13477 14.0549C5.13477 13.4723 5.56616 13 6.0983 13C6.63045 13 7.06184 13.4723 7.06184 14.0549C7.06184 14.6375 6.8515 14.9177 6.47963 15.4326L5.13477 17H7.06184");
}

.ll_t976_m {
  d: path("M20 16H12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
