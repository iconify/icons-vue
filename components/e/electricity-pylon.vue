<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uatv2xway"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electricity-pylon" /></template>
<style>
.uatv2xway {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 21.5l5-19h3l5 19M3.5 7h17m-15 4.5h13m-10.25 0l10.25 10m-2.75-10L5.5 21.5");
}

</style>
