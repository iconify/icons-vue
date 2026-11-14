<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhbflkxxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barbell-collar" /></template>
<style>
.dhbflkxxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5H13m5 0h3.5m-6-5zA2.5 2.5 0 0 1 18 10v5a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 13 15v-5a2.5 2.5 0 0 1 2.5-2.5m0 0v-3H19");
}

</style>
