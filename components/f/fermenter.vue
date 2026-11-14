<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="onc535byd"/><path class="w6_rv_dto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fermenter" /></template>
<style>
.onc535byd {
  d: path("M6.5 21.5V6h11v15.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6_rv_dto {
  d: path("m6.5 13.5l4 4h3l4-4m-5.5 4V20M10 6V2.5h4.5");
}

</style>
