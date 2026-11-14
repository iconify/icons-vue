<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_we5b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-receipt-no" /></template>
<style>
.bk_we5b5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.4 2.5H19v12.6m-2.663 5.175L14.5 21.5L12 20l-2.5 1.5L7.25 20L5 21.5V8.948M10.4 6.5h5.1M13.9 10h1.6m-7 3.5h1.1m-6.1-10l17 17");
}

</style>
