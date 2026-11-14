<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe75ddbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allergen-sesame" /></template>
<style>
.qe75ddbqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.238 15.5H2.5C2.5 8.5 6.5 4 11 4c3.624 0 6.924 2.919 8.071 7.711M6.25 11.25l1-1.75m3-1.5H12m2.75 1.5l1 1.75M18 14.5V18m0 3h.01");
}

</style>
