<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xofl4wgnc"/><circle class="ytopibb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kazoo-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xofl4wgnc {
  d: path("m3.74 11.11l16.52 1.78l.99.11v3.5l-.99.13l-16.52 2.24l-.99.13v-8z");
}

.ytopibb5c {
  cx: 12px;
  cy: 10px;
  r: 2px;
}

</style>
