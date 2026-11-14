<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltpm2e8rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barber-shop" /></template>
<style>
.ltpm2e8rl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5h4.5A1.75 1.75 0 0 1 16 6.75v10.5A1.75 1.75 0 0 1 14.25 19h-4.5A1.75 1.75 0 0 1 8 17.25V6.75A1.75 1.75 0 0 1 9.75 5m-2-2.5h8.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 16.25 5h-8.5A1.25 1.25 0 0 1 6.5 3.75A1.25 1.25 0 0 1 7.75 2.5m0 16.5h8.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-8.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 7.75 19M8 12l8-4m-8 8l8-3.75");
}

</style>
