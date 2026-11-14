<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dg0athhvc"/><path class="zjpa3ob-p"/><path class="m838ucczp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-clearing" /></template>
<style>
.dg0athhvc {
  d: path("M11.2 18.5H2.5v-13h19v6.7M6 9.5h5.5m-5.5 5h3.5");
}

.m838ucczp {
  d: path("m15.5 12.25l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjpa3ob-p {
  d: path("M20.531 16a3.5 3.5 0 1 1-3.031-1.75");
}

</style>
