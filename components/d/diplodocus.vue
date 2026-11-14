<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndlymbcmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diplodocus" /></template>
<style>
.ndlymbcmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15C6 14 7 11 11 11h3c2 0 3-2 3.5-5l.5-1.5c.5-1 3-1 3.5 0c0 1-1 1-1.5 1.5l-.5 4c-.5 4-2 6.5-5.5 6.5H9c-2.5 0-4-.5-5.5-1.5Zm6 1.5V21m5-4.5V21");
}

</style>
