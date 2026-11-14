<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-a017s7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cap-rate" /></template>
<style>
.m-a017s7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.249 21.5H6v-15l12-4v11.551M9.5 10h.01m4.99 0h.01M9.5 13.5h.01M9.5 17h.01M15 21l6-6m-5.5.5h.01m4.99 5h.01");
}

</style>
