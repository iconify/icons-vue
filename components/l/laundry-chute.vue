<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6vsj82gb"/><path class="epee33vep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laundry-chute" /></template>
<style>
.epee33vep {
  d: path("M9 5.5h6V10H9Zm3 7.5v5.75m-2.5-2.5l2.5 2.5l2.5-2.5");
}

.k6vsj82gb {
  d: path("M6.5 2.5h11a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
