<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfrpeflpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:developer-team" /></template>
<style>
.wfrpeflpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.163 20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.151 0 2.175.212 3.033.636M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M16 4.5a3.5 3.5 0 0 1 .906 6.881M16.25 14.5l-2.75 3.25L16.25 21m3-6.5L22 17.75L19.25 21");
}

</style>
