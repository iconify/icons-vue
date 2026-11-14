<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ub29l-bqr"/><path class="g8-w40bit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charging-complete" /></template>
<style>
.g8-w40bit {
  d: path("M8.5 9.5L7 12h2.5L8 14.5m3.5-2.5l1.75 1.75l3-3.5");
}

.ub29l-bqr {
  d: path("M2.5 7H19v10H2.5Zm19 3.5v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
