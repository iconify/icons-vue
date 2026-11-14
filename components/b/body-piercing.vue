<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="el6ejpbjk"/><path class="j6dui_bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-piercing" /></template>
<style>
.el6ejpbjk {
  d: path("M14 5.25a8 8 0 1 1-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6dui_bbd {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
