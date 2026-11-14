<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sehlnsflu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chore-assign" /></template>
<style>
.sehlnsflu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 21c0-4.5 3.5-7 7.5-7c2 0 3.75.6 5 1.5m-1 3h7m-2.75-2.75l2.75 2.75l-2.75 2.75");
}

</style>
