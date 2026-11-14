<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xrihk6bns"/><path class="jwstp3b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-checklist" /></template>
<style>
.jwstp3b1p {
  d: path("M8 2h6v3H8ZM6.5 8.5l1.25 1.25L10 7.5m-3.5 5l1.25 1.25L10 11.5m-3.5 5l1.25 1.25L10 15.5m2.5-6.75h3m-3 4h2.7M18 14.5V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrihk6bns {
  d: path("M15.2 19H3.5V3.5h15v8.2");
}

</style>
