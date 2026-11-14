<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t0_r4f9bt"/><path class="xg25v1prw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-size" /></template>
<style>
.t0_r4f9bt {
  d: path("m12 2.5l6.5 3.75v7.25L12 17.25L5.5 13.5V6.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg25v1prw {
  d: path("M5.5 6.25L12 10l6.5-3.75M12 10v7.25M4.5 20.5h15M6 19l-1.5 1.5L6 22m12-3l1.5 1.5L18 22");
}

</style>
