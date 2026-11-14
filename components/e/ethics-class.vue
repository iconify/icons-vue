<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3se-3bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ethics-class" /></template>
<style>
.q3se-3bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-6 0h12M4.5 6.5h15M2.5 12h6c0 3.5-6 3.5-6 0m3-5.5V12m10 0h6c0 3.5-6 3.5-6 0m3-5.5V12");
}

</style>
