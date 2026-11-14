<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n87ia_05w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buoy" /></template>
<style>
.n87ia_05w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16.75L10.5 6.5h3L17 16.75ZM12 6.5v-4M2.5 20.25q2.375-1.5 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
