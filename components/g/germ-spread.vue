<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsqegtvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:germ-spread" /></template>
<style>
.mhsqegtvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 16a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM8 12.75V11m3.25 5H13m-5 3.25V21m-3.25-5H3m7.25-2.25l1.25-1.25m-1.25 5.75l1.25 1.25m-5.75-1.25L4.5 19.5m1.25-5.75L4.5 12.5M8 8.25V2.5M5.75 4.75L8 2.5l2.25 2.25m3.5 5.5L21 3m-3 0h3v3m-5.25 10h5.75m-2.25-2.25L21.5 16l-2.25 2.25");
}

</style>
