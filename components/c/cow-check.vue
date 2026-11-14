<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd7oy51xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cow-check" /></template>
<style>
.vd7oy51xb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5h9.5a2 2 0 0 1 2 2V12a2 2 0 0 1-2 2H8v-2.5l-3 1A1.5 1.5 0 0 1 3 11V7.5A1.5 1.5 0 0 1 4.5 6zM4.75 6L4 3.5m3.5 3L8.25 4M9.5 14v6m8-6v1.3M14.75 18l2 2L21 15.75");
}

</style>
