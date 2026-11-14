<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivki3qerk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boundary-line" /></template>
<style>
.ivki3qerk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m15.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M5.5 19.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0-15h4.75m3 0H18M19.5 6v3.25m0 3v3.25M18 17.25l-3.25.75m-3 .5l-3.25.75M6.75 18l-1-4.5m-.5-3l-1-4.5");
}

</style>
