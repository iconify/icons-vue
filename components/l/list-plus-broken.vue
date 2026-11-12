<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qesyv5buv"/><path class="djbi_ub-i"/><path class="x_2hitbgb"/><path class="spodu6bqp"/><path class="i98cvin-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-plus-broken" /></template>
<style>
.djbi_ub-i {
  d: path("M11 18H3");
}

.i98cvin-m {
  d: path("M21 10L9.88235 10M5.38235 10H3");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qesyv5buv {
  d: path("M11 14L3 14");
}

.spodu6bqp {
  d: path("M3 6L14.1176 6M18.6176 6H21");
}

.x_2hitbgb {
  d: path("M21 16.5L17.5 16.5M17.5 16.5L14 16.5M17.5 16.5L17.5 13M17.5 16.5L17.5 20");
}

</style>
