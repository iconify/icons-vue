<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz_tbsbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-trigger" /></template>
<style>
.mz_tbsbpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5V4A1.5 1.5 0 0 1 5 2.5h6.5A1.5 1.5 0 0 1 13 4v17.5m-2.75-9h.01m9.24.75l-3.5 4h4l-3.5 4");
}

</style>
