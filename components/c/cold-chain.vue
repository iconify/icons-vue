<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isn_-dbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cold-chain" /></template>
<style>
.isn_-dbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.75h4a2.75 2.75 0 0 1 0 5.5h-4a2.75 2.75 0 0 1 0-5.5m6.5 0h4a2.75 2.75 0 0 1 0 5.5h-4a2.75 2.75 0 0 1 0-5.5m4.25-11v7.5M13.75 4.6l6.5 3.8m-6.5 0l6.5-3.8");
}

</style>
