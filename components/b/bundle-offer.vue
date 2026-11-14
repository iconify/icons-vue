<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktme8f42u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bundle-offer" /></template>
<style>
.ktme8f42u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8h14.5A1.75 1.75 0 0 1 21 9.75v1a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 10.75v-1A1.75 1.75 0 0 1 4.75 8m2.375 4.5h9.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 18.875v-3.75A2.625 2.625 0 0 1 7.125 12.5M12 8v13.5M12 8c-1.5-4.5-6-4-4 0m4 0c1.5-4.5 6-4 4 0");
}

</style>
