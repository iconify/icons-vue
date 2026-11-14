<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qac_0kbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airshow" /></template>
<style>
.qac_0kbrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19m-19-3.5c6 0 12-3 12-8.5c0-3-1.75-5-3.75-5s-3.5 1.75-3.5 4c0 4 4.25 7 9.25 7m0 0h5M18 11.5l2 3.5l-2 3.5m-1.5-5l.75 1.5l-.75 1.5");
}

</style>
