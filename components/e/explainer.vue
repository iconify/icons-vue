<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h632zwbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:explainer" /></template>
<style>
.h632zwbvb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5V12a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 12V6.5A3.5 3.5 0 0 1 6.5 3M12 15.5V18m-4 3.5l4-3.5l4 3.5m-9-14h8M7 11h4.5");
}

</style>
