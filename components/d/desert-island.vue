<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lwk_bl73s"/><path class="ueha0eb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desert-island" /></template>
<style>
.lwk_bl73s {
  d: path("M7 20q4.5-7 9 0");
}

.ueha0eb4e {
  d: path("M11.5 16.5Q11 11 14 6.5m0 0q-4.5-3-9 1m9-1q4.5-3 7.5.5M14 6.5Q18 8 19 12M2.5 20q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
