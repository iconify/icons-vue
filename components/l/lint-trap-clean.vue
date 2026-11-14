<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuu1rnbfv"/><path class="whkm84cib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lint-trap-clean" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuu1rnbfv {
  d: path("M15.4 19.5H2.5V4h16v11.4");
}

.whkm84cib {
  d: path("M6 13c0-2.5 2.5-3.5 4-2c1-2 4.5-1.75 5 2Zm12.5 2.5q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3Z");
}

</style>
