<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3qxo-t_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-bento" /></template>
<style>
.m3qxo-t_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h4A3.5 3.5 0 0 1 14 6.5V7a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 3 7v-.5A3.5 3.5 0 0 1 6.5 3M19 3za2 2 0 0 1 2 2v3.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2M5 13.5za2 2 0 0 1 2 2V19a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-3.5a2 2 0 0 1 2-2m8.5 0h4A3.5 3.5 0 0 1 21 17v.5a3.5 3.5 0 0 1-3.5 3.5h-4a3.5 3.5 0 0 1-3.5-3.5V17a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
