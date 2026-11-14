<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwfgepvvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aqueduct" /></template>
<style>
.xwfgepvvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h15A1.5 1.5 0 0 1 21 5v1.5A1.5 1.5 0 0 1 19.5 8h-15A1.5 1.5 0 0 1 3 6.5V5a1.5 1.5 0 0 1 1.5-1.5M3 8v13M21 8v13M3 14a3 3 0 0 1 6 0v7m0-7a3 3 0 0 1 6 0v7m0-7a3 3 0 0 1 6 0");
}

</style>
