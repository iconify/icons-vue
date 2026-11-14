<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="df3ik9obg"/><path class="ucf-3acpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cdn-cache" /></template>
<style>
.df3ik9obg {
  d: path("M7 18.5h10a4 4 0 0 0 .5-8A6 6 0 0 0 6 10a4.25 4.25 0 0 0 1 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucf-3acpg {
  d: path("m13 9l-2.5 3.5h3L11 16");
}

</style>
