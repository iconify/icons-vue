<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhcud0_iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keytar" /></template>
<style>
.jhcud0_iw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h10l2 2.5h4.5v3H17l-2 3.5H5A2.5 2.5 0 0 1 2.5 14v-4A2.5 2.5 0 0 1 5 7.5Zm2 0V12m3-4.5V12m3-4.5V12");
}

</style>
