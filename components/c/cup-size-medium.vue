<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tatj5ib8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cup-size-medium" /></template>
<style>
.tatj5ib8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6h11A1.5 1.5 0 0 1 19 7.5A1.5 1.5 0 0 1 17.5 9h-11A1.5 1.5 0 0 1 5 7.5A1.5 1.5 0 0 1 6.5 6m1 0l1-2.5h7l1 2.5m-10 3L8 21h8l1.5-12");
}

</style>
