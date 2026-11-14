<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spnu-rbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-race-pylon" /></template>
<style>
.spnu-rbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.5L10.25 4a1.75 1.75 0 0 1 3.5 0L16 21.5ZM9.75 8h4.5m-5 3h5.5m-6 4h6.5M8.5 18h7");
}

</style>
