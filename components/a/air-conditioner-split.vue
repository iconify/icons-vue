<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvjxmqbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-conditioner-split" /></template>
<style>
.nvjxmqbjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4H18a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 14H8.5A3.5 3.5 0 0 1 5 10.5v-3A3.5 3.5 0 0 1 8.5 4M5 11H4q-1.5 0-1.5 1.5V18M8 11h10.5M11 17l-.75 3m5.25-3l.75 3");
}

</style>
