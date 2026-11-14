<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y87dd4b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lux" /></template>
<style>
.y87dd4b1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19a9 9 0 0 1 18 0M12 7.25V5M6.25 8.75L5 6.75m12.75 2l1.25-2M12 19l2.75-4.75M12 19h.01");
}

</style>
