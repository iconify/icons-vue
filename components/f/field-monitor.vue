<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja8v2abtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-monitor" /></template>
<style>
.ja8v2abtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 6.5h11.75A2.625 2.625 0 0 1 20.5 9.125v3.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 12.875v-3.75A2.625 2.625 0 0 1 6.125 6.5M5 6.5L3 2.75h18L19 6.5m-7 9v2.25L8 21.5m-3 0h6");
}

</style>
