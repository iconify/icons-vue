<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ynnqgt8sp"/><path class="rhlnpmbpq"/><path class="vi7mzdtvt"/><path class="zbwqridka"/><path class="op1q6lnqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.op1q6lnqg {
  stroke-linejoin: round;
  d: path("M15 16.5L17.5 14L20 16.5M17.5 14V20");
}

.rhlnpmbpq {
  d: path("M21 10L3 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vi7mzdtvt {
  d: path("M11 14L3 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ynnqgt8sp {
  d: path("M21 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zbwqridka {
  d: path("M11 18H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
