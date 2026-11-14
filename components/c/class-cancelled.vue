<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apx2vccgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:class-cancelled" /></template>
<style>
.apx2vccgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.4 4.5h12.1v12.1M17.1 21H3.5V7.4m6-4.9v3.1m5-3.1V6m-11 3.5h2.1m7.8 0h7.1m-17-6l17 17");
}

</style>
