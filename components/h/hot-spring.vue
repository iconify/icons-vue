<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xciauuwmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hot-spring" /></template>
<style>
.xciauuwmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17a9.5 4 0 1 0 19 0a9.5 4 0 1 0-19 0m4.75-6.75c-1-1.5-1-2.5 0-3.75s1-2.5 0-4M12 10.25c-1-1.5-1-2.5 0-3.75s1-2.5 0-4m4.75 7.75c-1-1.5-1-2.5 0-3.75s1-2.5 0-4");
}

</style>
