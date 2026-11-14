<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q66ufcccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:craft-box" /></template>
<style>
.q66ufcccq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18l-1.75 8.5H4.75Zm4 0L5 6.25l.5-2.75L8 6.25L10 12M5 6.25h3m6.75 2C14.5 6 16 4.5 18 3.5c.5 2 .25 4-.75 5.75Zm1.25.5L14.75 12");
}

</style>
