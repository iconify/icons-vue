<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebwfdqb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contract-handshake" /></template>
<style>
.ebwfdqb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5zA1.75 1.75 0 0 1 6 9.25v4.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-4.5A1.75 1.75 0 0 1 4.25 7.5m15.5 0za1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 18 13.75v-4.5a1.75 1.75 0 0 1 1.75-1.75M6 9l3.5-3H13l5 3M6 14l4.5 3.5q1.5.75 3 0L18 14M9.5 6l4 4M10 11l2.75 2.75");
}

</style>
