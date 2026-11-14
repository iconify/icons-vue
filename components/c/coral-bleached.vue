<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv2cdm43s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coral-bleached" /></template>
<style>
.iv2cdm43s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.5v-13m0 12L6.5 10V5.5M12 12l5-5V4M2.5 20q2.375-2 4.75 0T12 20t4.75 0t4.75 0");
}

</style>
