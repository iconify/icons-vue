<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvyvbcc-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-cargo-pallet" /></template>
<style>
.zvyvbcc-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h5.25A2.625 2.625 0 0 1 13.5 5.625v4a2.625 2.625 0 0 1-2.625 2.625h-5.25A2.625 2.625 0 0 1 3 9.625v-4A2.625 2.625 0 0 1 5.625 3M13.5 19.9v.1h-2v-2.5H9V20H7v-2.5H4.5V20h-2v-5h11v2.6M8.25 3v9.25M19 14v7.75m-3-3l3-2.25l3 2.25m-4.5 3h3");
}

</style>
