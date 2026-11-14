<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="m4n7uujtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bookplate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4n7uujtw {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h5m-2-11h5A1.5 1.5 0 0 0 16.5 7v4a1.5 1.5 0 0 0-1.5 1.5h-5A1.5 1.5 0 0 0 8.5 11V7A1.5 1.5 0 0 0 10 5.5M11 9h3");
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

</style>
