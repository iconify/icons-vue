<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vay788w-x"/><path class="fwze4p0rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glass-stopper" /></template>
<style>
.fwze4p0rg {
  d: path("M10.5 7.5v3h-2l2 11h3l2-11h-2v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vay788w-x {
  d: path("M6 5a6 2.5 0 1 0 12 0A6 2.5 0 1 0 6 5Z");
}

</style>
