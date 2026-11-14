<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sytbmv_to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-shower" /></template>
<style>
.sytbmv_to {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V5m-6.5 5c0-3 3-5 6.5-5s6.5 2 6.5 5ZM8 13.5L7.5 17m4.5-3.5V18m4-4.5l.5 3.5M6 21h12");
}

</style>
