<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="h6htdwbeh"/><path class="e28tbrbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bathroom-layout" /></template>
<style>
.e28tbrbxb {
  d: path("M14.25 12.25a2 3.25 0 1 0 4 0a2 3.25 0 1 0-4 0Z");
}

.h6htdwbeh {
  d: path("M5.5 6H10v12H5.5ZM14 6h4.5v3H14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
