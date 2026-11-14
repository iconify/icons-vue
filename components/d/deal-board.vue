<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inyxggbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-board" /></template>
<style>
.inyxggbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H7m2.75 0h4.5M17 3h4.5M4 6.5h1.5A1.5 1.5 0 0 1 7 8v1.5A1.5 1.5 0 0 1 5.5 11H4a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 4 6.5m0 7.25h1.5a1.5 1.5 0 0 1 1.5 1.5v4.25A1.5 1.5 0 0 1 5.5 21H4a1.5 1.5 0 0 1-1.5-1.5v-4.25a1.5 1.5 0 0 1 1.5-1.5m7.25-7.25h1.5a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5V8a1.5 1.5 0 0 1 1.5-1.5m7.25 0H20A1.5 1.5 0 0 1 21.5 8v3.5A1.5 1.5 0 0 1 20 13h-1.5a1.5 1.5 0 0 1-1.5-1.5V8a1.5 1.5 0 0 1 1.5-1.5m0 9.25H20a1.5 1.5 0 0 1 1.5 1.5V18a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 1 17 18v-.75a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
