<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzzian_vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hourly-room" /></template>
<style>
.zzzian_vi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h7v3C11.25 9 8.5 9.75 8.5 12s2.75 3 2.75 6.5v3h-7v-3C4.25 15 7 14.25 7 12S4.25 9 4.25 5.5Zm-1.5 0h10m-10 19h10M16 15.25v6.25m0-2.5h6v2.5m-2.875-5.25za1.375 1.375 0 0 1 1.375 1.375A1.375 1.375 0 0 1 19.125 19a1.375 1.375 0 0 1-1.375-1.375a1.375 1.375 0 0 1 1.375-1.375");
}

</style>
