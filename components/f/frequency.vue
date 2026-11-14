<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a417gfbbs"/><path class="a4gbf3bzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frequency" /></template>
<style>
.a417gfbbs {
  d: path("M3 9.5q2.25-7.875 4.5 0t4.5 0t4.5 0t4.5 0");
}

.a4gbf3bzs {
  d: path("M3 16.5v2h9v-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
