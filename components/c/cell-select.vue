<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ssf75nnqh"/><path class="dqk22ubip"/><path class="gtx0hsbgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-select" /></template>
<style>
.dqk22ubip {
  d: path("M4 8.5h15v7H4Z");
}

.gtx0hsbgq {
  fill: currentColor;
  d: path("M18 15h3.5v3.5H18Z");
}

.ssf75nnqh {
  d: path("M2.5 7h18v10h-18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
