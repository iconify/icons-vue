<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="izf0xb2-s"/><path class="etrfzibrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laundry-facility" /></template>
<style>
.etrfzibrz {
  d: path("M8 13.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm0-7h.01m2.99 0h5");
}

.izf0xb2-s {
  d: path("M4.5 3h15v18h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
