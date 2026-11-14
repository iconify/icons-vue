<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnqzu248y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cauldron" /></template>
<style>
.qnqzu248y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5h16m-14.5 0a7 7 0 1 0 13 0m-11 8l-.75 3m9.75-3l.75 3m-5.25 5c-2.5 0-2.5-2 0-3.5c2.5 1.5 2.5 3.5 0 3.5m-2-19h.01");
}

</style>
