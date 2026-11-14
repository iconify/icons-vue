<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrve55l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beaver-dam" /></template>
<style>
.qrve55l1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.5h6.5A1.75 1.75 0 0 1 17 5.25A1.75 1.75 0 0 1 15.25 7h-6.5A1.75 1.75 0 0 1 7 5.25A1.75 1.75 0 0 1 8.75 3.5M6.25 7h11.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H6.25A1.75 1.75 0 0 1 4.5 8.75A1.75 1.75 0 0 1 6.25 7m-2 3.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 14H4.25a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M3 18q2.25-1.875 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
