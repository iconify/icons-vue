<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bb75ulb2s"/><path class="immtwmycm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-transfer" /></template>
<style>
.bb75ulb2s {
  d: path("M13.706 21.186A23 23 0 0 1 12 21.25c-4.4 0-8-1.25-8-2.75v-13C4 4 7.6 2.75 12 2.75S20 4 20 5.5v7.955");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.immtwmycm {
  d: path("M4 5.5C4 7 7.6 8.25 12 8.25S20 7 20 5.5M4 12c0 1.5 3.6 2.75 8 2.75q1.001-.001 1.933-.082m3.85-.777C19.155 13.395 20 12.727 20 12m-5.5 6h7m-5.25-1.75L14.5 18l1.75 1.75m3.5-3.5L21.5 18l-1.75 1.75");
}

</style>
