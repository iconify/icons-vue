<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yubjjdbth"/><path class="c7zikwrvh"/><path class="r3ky14b5u"/><path class="xc_fo9bdv"/><path class="f26ggybga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-broken" /></template>
<style>
.c7zikwrvh {
  stroke-linejoin: round;
  d: path("M17 21V22H16V21M8 21V22H7V21");
}

.f26ggybga {
  d: path("M17 14L17 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3ky14b5u {
  d: path("M11 11.5H4M20 11.5H15");
}

.xc_fo9bdv {
  d: path("M17 7L17 9");
}

.yubjjdbth {
  d: path("M4 10V13C4 16.7712 4 18.6569 5.17157 19.8284C6.34315 21 8.22876 21 12 21C15.7712 21 17.6569 21 18.8284 19.8284C20 18.6569 20 16.7712 20 13V10C20 6.22876 20 4.34315 18.8284 3.17157C17.6569 2 15.7712 2 12 2C8.22876 2 6.34315 2 5.17157 3.17157C4.51839 3.82475 4.22937 4.69989 4.10149 6");
}

</style>
