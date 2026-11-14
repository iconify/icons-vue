<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bty6q-qbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-pack" /></template>
<style>
.bty6q-qbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 9h10a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 16 20H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 9m13.5 3.5h2v4h-2M7.5 9V6.5a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2V9m-8 3v5m3-5v5m3-5v5");
}

</style>
