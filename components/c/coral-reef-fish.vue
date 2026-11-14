<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eftfqni-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coral-reef-fish" /></template>
<style>
.eftfqni-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.5c2-3.5 7-3.5 9 0L21.5 4v5L18 6.5c-2 3.5-7 3.5-9 0m3.25 0h.01M7.5 20v-8.5m0 5c-3 0-4.5-2-4.5-5M7.5 14c2.5 0 5-.5 5-2");
}

</style>
