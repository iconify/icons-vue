<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfroborgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barcode-scanner" /></template>
<style>
.tfroborgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5h10.5a2 2 0 0 1 2 2V10a2 2 0 0 1-2 2h-4L10 20H6l1.5-8H5a2 2 0 0 1-2-2V7.5a2 2 0 0 1 2-2m15 0l1.5-.75m-1.5 4h1.75M20 12l1.5.75");
}

</style>
