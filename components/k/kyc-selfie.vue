<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6bl4yb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kyc-selfie" /></template>
<style>
.n6bl4yb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM4.5 20.5c.5-4 3.5-6 7.5-6s7 2 7.5 6M2.5 6V3.5H5");
}

</style>
