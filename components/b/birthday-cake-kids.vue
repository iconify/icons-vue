<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8iopca-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birthday-cake-kids" /></template>
<style>
.o8iopca-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18v-2.5A3.5 3.5 0 0 1 7 12m0 0V7.75M12 12V7.75M17 12V7.75M7 3c1.75 2 1.5 4.75 0 4.75S5.25 5 7 3m5 0c1.75 2 1.5 4.75 0 4.75S10.25 5 12 3m5 0c1.75 2 1.5 4.75 0 4.75S15.25 5 17 3");
}

</style>
