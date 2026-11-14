<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcyl-mk6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-bay" /></template>
<style>
.zcyl-mk6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5L12 3l9.5 5.5m-17 0V21m15-12.5V21m-8.079-9h3.658a1.5 1.5 0 0 1 1.455 1.864l-.25 1A1.5 1.5 0 0 1 14.829 16h-3.158a1.5 1.5 0 0 1-1.455-1.136l-.25-1A1.5 1.5 0 0 1 11.421 12M7.5 11h1l2 5m.5 3h.01m4.49 0h.01");
}

</style>
