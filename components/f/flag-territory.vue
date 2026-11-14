<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za99y3b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flag-territory" /></template>
<style>
.za99y3b9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3v15.5M8 4q3-1.5 6 .25q2.5 1.5 5.5.25V11q-3 1.25-5.5-.25Q11 9 8 10.5M3 21q9-6 18 0");
}

</style>
