<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="feuulsbjf"/><path class="xg_hzhwnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blue-green-deploy" /></template>
<style>
.feuulsbjf {
  fill: currentColor;
  d: path("M2.5 5h5v14h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg_hzhwnj {
  d: path("M16.5 5h5v14h-5Zm-6.25 4h3.5m-1.5-1.5l1.5 1.5l-1.5 1.5m1.5 4.5h-3.5m1.5-1.5l-1.5 1.5l1.5 1.5");
}

</style>
