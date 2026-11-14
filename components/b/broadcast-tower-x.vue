<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="po2pceb7v"/><path class="t7d3qq74q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broadcast-tower-x" /></template>
<style>
.po2pceb7v {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.t7d3qq74q {
  d: path("m6.5 21.5l5.5-13l1.942 4.59M16 3.5a4.5 4.5 0 0 1 0 6m3-7a8 8 0 0 1 0 8m-11-7a4.5 4.5 0 0 0 0 6m-3-7a8 8 0 0 0 0 8m10.5 5l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
