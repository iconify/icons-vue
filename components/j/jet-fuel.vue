<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oii1axwoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jet-fuel" /></template>
<style>
.oii1axwoo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h2L8 7h10.5a2.5 2.5 0 0 1 0 5H6c-1.5 0-2.5-1-2.75-2.5Zm10 9.5l-3 4.5H7m11-1.75c-1 1.25-2.75 3-2.75 4.25a2.75 2.75 0 0 0 5.5 0c0-1.25-1.75-3-2.75-4.25");
}

</style>
