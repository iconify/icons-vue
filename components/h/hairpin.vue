<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd7ka-e7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hairpin" /></template>
<style>
.qd7ka-e7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 18.5L14.75 5a1.75 1.75 0 0 1 2.75 2m0 0c-.75 1.25-1 1-2 2c-.75 1.25 0 1.75-.75 3c-1 1.25-1.75.75-2.5 2c-1 1.25-.25 1.75-1 3c-1 1.25-1.5 1-2.5 2.25l-.25 1.5");
}

</style>
