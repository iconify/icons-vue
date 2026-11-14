<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okcsvojhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antidote" /></template>
<style>
.okcsvojhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7v11.25a3.25 3.25 0 0 0 6.5 0V7M5.75 2.5h6a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 11.75 7h-6A1.75 1.75 0 0 1 4 5.25v-1A1.75 1.75 0 0 1 5.75 2.5m-.25 10H12m6 2.5v6m-3-3h6");
}

</style>
