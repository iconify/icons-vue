<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvq5j_j1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-interest-calendar" /></template>
<style>
.hvq5j_j1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 21H3.5V4.5h17v7.1M8 2.5v4m8-4v4m-12.5 3h17M8 13.5h.01m3.99 0h.01M8 17h.01m7.24 3.75l5.5-5.5m-5.25.25h.01m4.99 5h.01");
}

</style>
