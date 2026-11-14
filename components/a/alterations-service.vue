<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ngbwb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alterations-service" /></template>
<style>
.v_ngbwb2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.652 12.346L12 9.5l-2.75 12H3.5L5 2.5h14l.645 8.175m-6.099 5.57l-.224-.974M5 6h14m-4.75 14a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2.25-1.75l4.25-5m-1.25 5l-4.25-5");
}

</style>
