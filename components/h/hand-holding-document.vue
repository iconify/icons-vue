<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe90s-v0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-holding-document" /></template>
<style>
.qe90s-v0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5H6c1 0 1.75.5 2.5 1.25l1.5 1.5h4.5l4.25-3.5a1.75 1.75 0 0 1 2 2.25L16 20.25c-.5.5-1 .75-1.75.75H2.5m8.625-18.5h2.75A2.625 2.625 0 0 1 16.5 5.125v4.25A2.625 2.625 0 0 1 13.875 12h-2.75A2.625 2.625 0 0 1 8.5 9.375v-4.25A2.625 2.625 0 0 1 11.125 2.5M11 5.75h3m-3 3h2");
}

</style>
