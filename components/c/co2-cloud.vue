<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xutlz_lay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:co2-cloud" /></template>
<style>
.xutlz_lay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.5a2.5 2.5 0 0 1 0-5a3.75 3.75 0 0 1 7.25.5a2.25 2.25 0 0 1 .25 4.5Zm-.379 7.621a3 3 0 1 1 0-4.242M9 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0m7.75 1.75c.15-.85.85-1.25 1.75-1.25s1.75.6 1.75 1.5c0 1.4-3.5 2.5-3.5 3.75h3.5");
}

</style>
