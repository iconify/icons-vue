<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfo2bybkj"/><path class="wha1jbjcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-payment-methods" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfo2bybkj {
  d: path("M13 12.25h5a3.5 3.5 0 0 1 3.5 3.5v1.5a3.5 3.5 0 0 1-3.5 3.5h-5a3.5 3.5 0 0 1-3.5-3.5v-1.5a3.5 3.5 0 0 1 3.5-3.5");
}

.wha1jbjcw {
  d: path("M7 16.5L6.25 12a2 2 0 0 1 1.5-2.25l8-1.5A2 2 0 0 1 18 9.75M3.75 11.5L3 10a2 2 0 0 1 1.25-2.75l7.5-2.5a2 2 0 0 1 2.5 1m-4.75 10h12m-9.25 3h3");
}

</style>
