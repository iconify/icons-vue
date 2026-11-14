<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmetalb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foot-care" /></template>
<style>
.gmetalb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.813 12.249C18.187 11.677 17.18 11.295 16 11l-3.5-1C11 9.5 10 8.5 10 7V2.5H4.5V10c-1.5 1.25-2 2.75-2 4c0 1.5 1 2.5 2.5 2.5h7.238M18 21c-1.75-1.25-3-2.5-3-4c0-1.25.75-2 1.75-2c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c1 0 1.75.75 1.75 2c0 1.5-1.25 2.75-3 4");
}

</style>
