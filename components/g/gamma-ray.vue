<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vlkep1bth"/><path class="a75jntbgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gamma-ray" /></template>
<style>
.a75jntbgd {
  d: path("m18.5 9l3 3l-3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vlkep1bth {
  d: path("M2.5 12L5 6.5l3.5 11l3.5-11l3 9l1.75-3.5h4.75");
}

</style>
