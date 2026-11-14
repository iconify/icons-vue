<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-3dbpmbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colourist" /></template>
<style>
.x-3dbpmbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c5.5 0 9.5 4 9.5 8.5c0 3-2 4.5-4.5 4.5h-1.5a2 2 0 0 0-1.5 3.25c.75 1 .25 2.75-2 2.75c-5.25 0-9.5-4.25-9.5-9.5S6.75 2.5 12 2.5m-5 10h.01m2.24-5h.01m5.49-.25h.01");
}

</style>
