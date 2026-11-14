<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_3fwvjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-breed-dachshund" /></template>
<style>
.eh_3fwvjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 10h10L17 6.75q.75-1 1.75-.5l2.5 3q.75 1.5-.75 1.75h-2.25l-1 4H5.5a2.5 2.5 0 0 1 0-5m-1.25.25L2.5 8m4 7v3m9-3v3");
}

</style>
