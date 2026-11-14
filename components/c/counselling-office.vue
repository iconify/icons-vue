<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb0rd2x1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:counselling-office" /></template>
<style>
.eb0rd2x1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.75V6.25a2 2 0 0 1 4 0v6.5h3.75v5Zm4-8h2.75a1 1 0 0 1 1 1v2m-6.75 5v2m5.75-2v2m12.25-2V6.25a2 2 0 0 0-4 0v6.5h-3.75v5Zm-4-8h-2.75a1 1 0 0 0-1 1v2m6.75 5v2m-5.75-2v2");
}

</style>
