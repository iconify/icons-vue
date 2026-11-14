<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ivc5boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ear-defenders" /></template>
<style>
.l3ivc5boa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 10.5v-1a6.25 6.25 0 0 1 12.5 0v1m-12.5 0zA3.25 3.25 0 0 1 9 13.75v3.5a3.25 3.25 0 0 1-3.25 3.25a3.25 3.25 0 0 1-3.25-3.25v-3.5a3.25 3.25 0 0 1 3.25-3.25m12.5 0za3.25 3.25 0 0 1 3.25 3.25v3.5a3.25 3.25 0 0 1-3.25 3.25A3.25 3.25 0 0 1 15 17.25v-3.5a3.25 3.25 0 0 1 3.25-3.25");
}

</style>
