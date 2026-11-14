<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8-7hacbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-hockey-goal" /></template>
<style>
.f8-7hacbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5V4h16v10.4M7.75 4v10.5M13.25 4v10.5M2.5 9.25h16m3 5.75L18 20c-.75 1-2.25 1.5-3.25.75m.75-3.25h.01");
}

</style>
