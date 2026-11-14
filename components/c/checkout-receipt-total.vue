<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqffzwbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-receipt-total" /></template>
<style>
.iqffzwbrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3h10.5A1.75 1.75 0 0 1 19 4.75v14.234A1.17 1.17 0 0 1 17.25 20l-.882-.504a1.75 1.75 0 0 0-1.736 0l-1.764 1.008a1.75 1.75 0 0 1-1.736 0l-1.764-1.008a1.75 1.75 0 0 0-1.736 0L6.75 20A1.17 1.17 0 0 1 5 18.984V4.75A1.75 1.75 0 0 1 6.75 3M8.5 7h3m-3 3.5h3m4-3.5h.01m-.01 3.5h.01m-7.01 4h7");
}

</style>
