<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7hcv3b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bobbin" /></template>
<style>
.c7hcv3b8b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h10A1.5 1.5 0 0 1 17.5 4A1.5 1.5 0 0 1 16 5.5H6A1.5 1.5 0 0 1 4.5 4A1.5 1.5 0 0 1 6 2.5m0 16h10a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20A1.5 1.5 0 0 1 6 18.5m1.5-13v13m7-13v13m-7-6.5h7m-7 3h7m-7-6h7c4.5 0 3 5 6 6.5");
}

</style>
