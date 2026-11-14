<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bthtq9f-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cake-tin" /></template>
<style>
.bthtq9f-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9a8.5 3 0 1 0 17 0a8.5 3 0 1 0-17 0m0 0v6m17-6v6m-17 0a8.5 3 0 0 0 17 0m0-5.25h2v3h-2");
}

</style>
