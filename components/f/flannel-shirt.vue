<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emu-asuad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flannel-shirt" /></template>
<style>
.emu-asuad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.5 3l-4 2C3.5 5.5 3 6.5 3 7.5L2.5 20h3l1-10v11h11V10l1 10h3L21 7.5c0-1-.5-2-1.5-2.5l-4-2L12 7ZM12 7v14m-5.5-7h11");
}

</style>
