<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcnv_hgku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-sharp" /></template>
<style>
.lcnv_hgku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 7.5l9 9m0-9l-9 9M4.5 3H6a1.5 1.5 0 0 1 1.5 1.5V6A1.5 1.5 0 0 1 6 7.5H4.5A1.5 1.5 0 0 1 3 6V4.5A1.5 1.5 0 0 1 4.5 3M18 3h1.5A1.5 1.5 0 0 1 21 4.5V6a1.5 1.5 0 0 1-1.5 1.5H18A1.5 1.5 0 0 1 16.5 6V4.5A1.5 1.5 0 0 1 18 3M4.5 16.5H6A1.5 1.5 0 0 1 7.5 18v1.5A1.5 1.5 0 0 1 6 21H4.5A1.5 1.5 0 0 1 3 19.5V18a1.5 1.5 0 0 1 1.5-1.5m13.5 0h1.5A1.5 1.5 0 0 1 21 18v1.5a1.5 1.5 0 0 1-1.5 1.5H18a1.5 1.5 0 0 1-1.5-1.5V18a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
