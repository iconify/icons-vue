<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awxv7gbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flotation-cushion" /></template>
<style>
.awxv7gbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 4q6.5-1.5 13 0q2.5.5 2.5 4t-2.5 4q-6.5 1.5-13 0Q3 11.5 3 8t2.5-4Zm-3 12.75q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M7 20.25q2.25 1.5 4.5 0t4.5 0t4.5 0");
}

</style>
