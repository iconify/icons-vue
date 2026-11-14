<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3hmtcb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-fixed-ladder" /></template>
<style>
.j3hmtcb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l5-19m1 19l5-19M4.75 17h6M6 12h6M7.25 7h6m-6 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M11 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3.75-5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
