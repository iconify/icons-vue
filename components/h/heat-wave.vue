<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkpsc943o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heat-wave" /></template>
<style>
.pkpsc943o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-4 0h1.75m10.5 0H19M12 2v1.25M7 3.5l1.25 1.25M17 3.5l-1.25 1.25M8 21q1-1.5 0-3t0-3m4 6q1-1.5 0-3t0-3m4 6q1-1.5 0-3t0-3");
}

</style>
