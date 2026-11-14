<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of2f83_rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:humidifier-on" /></template>
<style>
.of2f83_rl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5H9a3.5 3.5 0 0 1 3.5 3.5v3.5A3.5 3.5 0 0 1 9 19H7.5A3.5 3.5 0 0 1 4 15.5V12a3.5 3.5 0 0 1 3.5-3.5m5.886 13H4.25q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041q-.057-.024-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099q-.034-.051-.063-.105t-.053-.111t-.041-.115t-.03-.119t-.018-.121Q3 20.311 3 20.25t.006-.123q.006-.061.018-.121t.03-.119t.041-.115t.053-.111t.063-.105q.034-.052.073-.099t.082-.091q.044-.043.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018Q4.189 19 4.25 19h8M6.5 5.75c-1.25-1 1.25-2.25 0-3.25M10 5.75c-1.25-1 1.25-2.25 0-3.25m6 13.25a3 3 0 1 0 4 0m-2-1.25v3");
}

</style>
