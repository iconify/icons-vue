<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3z67jbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biohazard" /></template>
<style>
.z3z67jbup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 4.25a3.75 3.75 0 1 1-6 0a3 3 0 0 0 6 0m2.75 15a3.75 3.75 0 1 1 3-5.25a3 3 0 0 0-3 5.25M3.25 14a3.75 3.75 0 1 1 3 5.25a3 3 0 0 0-3-5.25m7.5-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
