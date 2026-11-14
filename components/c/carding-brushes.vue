<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="see9s_2dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carding-brushes" /></template>
<style>
.see9s_2dj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7h12l6.5-3.5M21 17H9l-6.5 3.5M4.5 7v2.5m3-2.5v2.5m3-2.5v2.5m3-2.5v2.5m-3 7.5v-2.5m3 2.5v-2.5m3 2.5v-2.5m3 2.5v-2.5");
}

</style>
