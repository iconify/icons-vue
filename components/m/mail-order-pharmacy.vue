<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbuoc2hwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mail-order-pharmacy" /></template>
<style>
.lbuoc2hwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 11.5h12.75A2.625 2.625 0 0 1 21 14.125v4.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-4.75A2.625 2.625 0 0 1 5.625 11.5m5.125-9h2.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1m0 2h2.5A1.75 1.75 0 0 1 15 6.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 9.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M3 14.5h18m-9 0v3");
}

</style>
