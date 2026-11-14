<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf3x_pbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cleaning-spray" /></template>
<style>
.gf3x_pbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7V4.5A1.5 1.5 0 0 1 8.5 3h4.879a1.5 1.5 0 0 1 1.06.439l.811.811a.732.732 0 0 1-.518 1.25H13.5A1.5 1.5 0 0 0 12 7a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 7 7m0 1.5L4.5 12v8A1.5 1.5 0 0 0 6 21.5h8a1.5 1.5 0 0 0 1.5-1.5v-8L12 8.5Zm12.5-5.75h.01m.74 2.75h.01m-.76 2.75h.01");
}

</style>
