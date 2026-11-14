<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqm94actk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leave-calendar" /></template>
<style>
.xqm94actk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 9a2.75 2.75 0 1 0 5.5 0A2.75 2.75 0 1 0 2 9m0 9c0-2.5 1.25-3.75 2.75-3.75S7.5 15.5 7.5 18Zm14.5-9A2.75 2.75 0 1 0 22 9a2.75 2.75 0 1 0-5.5 0m0 9c0-2.5 1.25-3.75 2.75-3.75S22 15.5 22 18ZM12.941 6.416a2.75 2.75 0 0 1 1.643 1.643m0 1.882a2.75 2.75 0 0 1-1.643 1.643m-1.882 0a2.75 2.75 0 0 1-1.643-1.643m0-1.882a2.75 2.75 0 0 1 1.643-1.643M9.25 18c0-1.5.5-2.75 1.25-3.25m3 0c.75.5 1.25 1.75 1.25 3.25M11 18h2");
}

</style>
