<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pdm45_o_b"/><path class="w_otj1bev"/><path class="e1uudcbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heart-outline-thin" /></template>
<style>
.e1uudcbua {
  d: path("m4 9 8 8 8 -8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdm45_o_b {
  d: path("M4 9a4 4 0 0 1 8 0");
}

.w_otj1bev {
  d: path("M12 9a4 4 0 0 1 8 0");
}

</style>
