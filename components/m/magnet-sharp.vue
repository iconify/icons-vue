<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8a0xgb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnet-sharp" /></template>
<style>
.c8a0xgb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h4.5V13.5a2.75 2.75 0 0 0 5.5 0V2.75h4.5V13.5a7.25 7.25 0 0 1-14.5 0Zm0 4.5h4.5m5.5 0h4.5");
}

</style>
