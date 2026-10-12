<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o_wg9vwpx"/><path class="pv4d0uykc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:directions" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_wg9vwpx {
  d: path("m13.59 4.34l6.07 6.07q1.59 1.59 0 3.18l-6.07 6.07q-1.59 1.59-3.18 0l-6.07-6.07q-1.59-1.59 0-3.18l6.07-6.07q1.59-1.59 3.18 0");
}

.pv4d0uykc {
  d: path("M9.25 15.25V13a2 2 0 0 1 2-2h4.5M13.5 8.75L15.75 11l-2.25 2.25");
}

</style>
