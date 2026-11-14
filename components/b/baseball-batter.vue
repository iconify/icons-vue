<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icdkxtt4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseball-batter" /></template>
<style>
.icdkxtt4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 21.5c0-4 3-7.5 7-7.5s7 3.5 7 7.5m-2-7za.62.62 0 0 0 .8-.222l5.8-9.113A1.513 1.513 0 0 0 20.5 3a1.565 1.565 0 0 0-2.145.798l-4.14 9.936a.6.6 0 0 0 .285.766");
}

</style>
