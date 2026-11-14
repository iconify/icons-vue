<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6p8zvb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:channel-number" /></template>
<style>
.i6p8zvb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19v13.5h-19ZM8 3l4 5l4-5m-5 7.5l-1 6.75m4.5-6.75l-1 6.75m-5-5H16m-8 3.5h7.5");
}

</style>
