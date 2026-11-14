<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecs_38bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:instance-group" /></template>
<style>
.ecs_38bml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.375 3.5h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25A2.625 2.625 0 0 1 13.625 12h-3.25A2.625 2.625 0 0 1 7.75 9.375v-3.25A2.625 2.625 0 0 1 10.375 3.5M6.125 12h3.25A2.625 2.625 0 0 1 12 14.625v3.25A2.625 2.625 0 0 1 9.375 20.5h-3.25A2.625 2.625 0 0 1 3.5 17.875v-3.25A2.625 2.625 0 0 1 6.125 12m8.5 0h3.25a2.625 2.625 0 0 1 2.625 2.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-3.25A2.625 2.625 0 0 1 12 17.875v-3.25A2.625 2.625 0 0 1 14.625 12M7.75 6.25h8.5M3.5 14.75H12m0 0h8.5");
}

</style>
