<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae71h-bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:berth-free" /></template>
<style>
.ae71h-bkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19h19m-19-7h8.25L9 16H4.25Zm4.25 0V5L10 9.5H6.75M16 7h-2.5v2.75m0 2.75v2.75m0 2.5V19M19 7h2.5v2.75m0 2.75v2.75m0 2.5V19");
}

</style>
