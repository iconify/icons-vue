<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpd549bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beer-crate" /></template>
<style>
.hpd549bfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 11.5h12.75A2.625 2.625 0 0 1 21 14.125v4.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-4.75A2.625 2.625 0 0 1 5.625 11.5m-.125 0v-3l1-2v-3h1v3l1 2v3m2 0v-3l1-2v-3h1v3l1 2v3m2 0v-3l1-2v-3h1v3l1 2v3m-9 5h5");
}

</style>
