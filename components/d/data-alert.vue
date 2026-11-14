<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clychlg-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-alert" /></template>
<style>
.clychlg-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 17v-6.5a6.5 6.5 0 0 1 13 0V17l1.5 1.75H4zm4.5 4.5h4M9 15v-2.5m3 2.5V9m3 6v-4");
}

</style>
