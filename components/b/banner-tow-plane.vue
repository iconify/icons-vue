<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2n28k7gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banner-tow-plane" /></template>
<style>
.p2n28k7gi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h13.5a1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 17.75 11H4.25A1.75 1.75 0 0 1 2.5 9.25v-5A1.75 1.75 0 0 1 4.25 2.5M6 6.75h10M11 11l1.842 3.438M14.75 18h6.75M19 18l-2.25-3.5M19 18l-2.25 3.5m-2-5v3");
}

</style>
