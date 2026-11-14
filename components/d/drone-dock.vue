<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyij3b63s"/><path class="vh4abz0lt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-dock" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pyij3b63s {
  d: path("M2.5 11v7.5A2.5 2.5 0 0 0 5 21h14a2.5 2.5 0 0 0 2.5-2.5V11M6 4.5V8h12V4.5");
}

.vh4abz0lt {
  d: path("M11.688 8h.625a2.19 2.19 0 0 1 2.187 2.188v.125a2.19 2.19 0 0 1-2.187 2.187h-.625A2.19 2.19 0 0 1 9.5 10.313v-.125A2.19 2.19 0 0 1 11.688 8M3 4.5h6m6 0h6");
}

</style>
