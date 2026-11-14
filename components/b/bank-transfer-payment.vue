<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8sfxabsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-transfer-payment" /></template>
<style>
.e8sfxabsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.25 8.25l5.25-5l5.25 5Zm0 2.5h10.5M3.25 20.5h8.3M5 13.25V18m3.5-4.75V18m3.5-4.75V18m3-2.25h6m-1.5-1.5l1.5 1.5M21 20h-6m1.5 1.5L15 20");
}

</style>
