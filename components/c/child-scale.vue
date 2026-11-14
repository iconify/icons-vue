<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sa-7u02bz"/><path class="scgvdhw-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:child-scale" /></template>
<style>
.sa-7u02bz {
  d: path("M2.5 3h19c0 4.5-4 6.5-9.5 6.5S2.5 7.5 2.5 3ZM12 9.5v3m-8.5 0h17v9h-17Z");
}

.scgvdhw-l {
  d: path("M10.5 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
