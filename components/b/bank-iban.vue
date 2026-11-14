<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bzb_h2b9k"/><path class="hrsb_ybcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-iban" /></template>
<style>
.bzb_h2b9k {
  d: path("M7.25 2.5L5.75 14m6.5-11.5L10.75 14M3.5 6.25h11.25M3 10.25h11.25M2.5 19.5h1.25m2.75 0h1.25m5.75-2a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm0 0h8");
}

.hrsb_ybcn {
  d: path("M17.5 13.5c-2 2-2 6 0 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
