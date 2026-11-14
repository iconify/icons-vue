<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grq9za1de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-umbrella" /></template>
<style>
.grq9za1de {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5a9.5 9 0 0 1 19 0a2.375 1.75 0 0 0-4.75 0a2.375 1.75 0 0 0-4.75 0a2.375 1.75 0 0 0-4.75 0a2.375 1.75 0 0 0-4.75 0m9.5 0v6a2 2 0 0 1-4 0");
}

</style>
