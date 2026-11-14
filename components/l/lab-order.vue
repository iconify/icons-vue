<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="olsgfqz6y"/><path class="pasxli_ph"/><path class="q15aztb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-order" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.olsgfqz6y {
  d: path("M5 2.5v13C5 17.4 6.6 19 8.5 19s3.5-1.6 3.5-3.5v-13m-8.5 0h10");
}

.pasxli_ph {
  fill: currentColor;
  d: path("M5 11h7v4.5c0 1.9-1.6 3.5-3.5 3.5S5 17.4 5 15.5Z");
}

.q15aztb6y {
  d: path("M18 14.5v7M14.5 18h7");
}

</style>
