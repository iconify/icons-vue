<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgrmizwfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gadget-water-damage" /></template>
<style>
.cgrmizwfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.875 2.5h.75A4.375 4.375 0 0 1 13 6.875v10.25A4.375 4.375 0 0 1 8.625 21.5h-.75A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5M6.5 18.5H10M18 7s3 3.5 3 6a3 3 0 0 1-6 0c0-2.5 3-6 3-6");
}

</style>
