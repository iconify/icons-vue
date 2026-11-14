<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky7zihbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-16mm" /></template>
<style>
.ky7zihbfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v19M7.5 5za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 7.5 8a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 7.5 5m0 11za1.25 1.25 0 0 1 1.25 1.25v.5A1.25 1.25 0 0 1 7.5 19a1.25 1.25 0 0 1-1.25-1.25v-.5A1.25 1.25 0 0 1 7.5 16m5.75-11H16a1.75 1.75 0 0 1 1.75 1.75v10.5A1.75 1.75 0 0 1 16 19h-2.75a1.75 1.75 0 0 1-1.75-1.75V6.75A1.75 1.75 0 0 1 13.25 5");
}

</style>
