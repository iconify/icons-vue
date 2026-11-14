<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cllctpd7v"/><path class="g8twj458s"/><path class="o_sf0d6sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-branch-lock" /></template>
<style>
.cllctpd7v {
  d: path("M3.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 7v14");
}

.g8twj458s {
  d: path("M17 7c0 5.5-11 4.5-11 10m10.188 0h3.625A2.19 2.19 0 0 1 22 19.188v.625A2.19 2.19 0 0 1 19.813 22h-3.625A2.19 2.19 0 0 1 14 19.813v-.625A2.19 2.19 0 0 1 16.188 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_sf0d6sq {
  d: path("M15.5 17v-1.25a2.5 2.5 0 0 1 5 0V17");
}

</style>
