<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o79lv490u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-sesame" /></template>
<style>
.o79lv490u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.238 15.5H2.5C2.5 8.5 6.5 4 11 4c3.694 0 7.052 3.033 8.136 7.992M6.25 11.25l1-1.75m3-1.5H12m2.75 1.5l1 1.75M18 14.5V18m0 3h.01");
}

</style>
