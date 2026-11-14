<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdn2poqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-bag" /></template>
<style>
.fhdn2poqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 8.5h10.25a4.375 4.375 0 0 1 4.375 4.375v2.75A4.375 4.375 0 0 1 17.125 20H6.875A4.375 4.375 0 0 1 2.5 15.625v-2.75A4.375 4.375 0 0 1 6.875 8.5m1.625 0c0-5 7-5 7 0m-9 0V20m11-11.5V20m-11-7.5h11");
}

</style>
