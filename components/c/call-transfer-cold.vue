<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n2wyw8v7p"/><path class="xb3q1rb3w"/><path class="yf_1wthty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-transfer-cold" /></template>
<style>
.n2wyw8v7p {
  d: path("M5 3h3l2 5l-2.5 2c1 2.5 4 5.5 6.5 6.5l2-2.5l5 2v3a2 2 0 0 1-2 2c-8.5-.5-15.5-7.5-16-16a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb3q1rb3w {
  d: path("M13 11c0-4 2.5-6 7-6");
}

.yf_1wthty {
  d: path("M17.5 2.5L20 5l-2.5 2.5");
}

</style>
