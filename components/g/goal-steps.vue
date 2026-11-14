<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwvgrhbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goal-steps" /></template>
<style>
.lwvgrhbci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h4.5V16H12v-4.5h4.5V7h2m0 0V3.5m.914.406l.211.094a.547.547 0 0 1 0 1l-.211.094A.65.65 0 0 1 18.5 4.5a.65.65 0 0 1 .914-.594");
}

</style>
