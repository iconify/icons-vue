<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3o1_qu2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carbon-capture-plant" /></template>
<style>
.l3o1_qu2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5v-6.151a1.5 1.5 0 0 1 .728-1.286l2.986-1.791A.849.849 0 0 1 8 11a.849.849 0 0 0 1.286.728l2.428-1.456A.849.849 0 0 1 13 11v.25a1.25 1.25 0 0 0 1.25 1.25a1.25 1.25 0 0 0 1.25-1.25v-.75A1.5 1.5 0 0 1 17 9h2a1.5 1.5 0 0 1 1.5 1.5v9A1.5 1.5 0 0 1 19 21H4.5A1.5 1.5 0 0 1 3 19.5m3.5-3V18m4-1.5V18M18 2.5v3.75M16.25 4.5L18 6.25l1.75-1.75");
}

</style>
