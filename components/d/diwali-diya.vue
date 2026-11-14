<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0asphbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diwali-diya" /></template>
<style>
.o0asphbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c0 4.5 4 7 9 7c4 0 7-2 9.5-7c-3.5 1-6.5.5-9.5.5c-3.5 0-6.5-.5-9-.5m10-2.25C11.5 8.9 11.25 7 13 4.5c1.75 2.5 1.5 4.4 0 5.25");
}

</style>
