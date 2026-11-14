<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abzal6b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:border-checkpoint" /></template>
<style>
.abzal6b2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5V8l3-3l3 3v12.5Zm10-10v10M13 7h7a1.5 1.5 0 0 1 1.5 1.5V9a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 11.5 9v-.5A1.5 1.5 0 0 1 13 7m2.5 0l-1 3.5M19 7l-1 3.5");
}

</style>
