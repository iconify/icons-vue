<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="up5bnccaf"/><path class="oe_ries_t"/><circle class="tsn5jyb8z"/><path class="zd2j9r4ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:debt-sharp" /></template>
<style>
.oe_ries_t {
  d: path("m6.59 6.59l3.14 3.14");
}

.tsn5jyb8z {
  cx: 14.5px;
  cy: 14.5px;
  r: 6.75px;
}

.up5bnccaf {
  cx: 5px;
  cy: 5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zd2j9r4ef {
  d: path("m16.31 13.04l-.435-1.08H12.89v1.33c0 1.77 3.56.99 3.56 2.88v1.36h-3.18l-.54-1.08");
}

</style>
