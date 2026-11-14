<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj9_4_jfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-map" /></template>
<style>
.gj9_4_jfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 5.5h1.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12.75 9h-1.5A1.75 1.75 0 0 1 9.5 7.25a1.75 1.75 0 0 1 1.75-1.75M9.5 7.25H5V3.5m9.5 3.75H19V3.5m-16.5 0h5m9 0h5M6.026 12.908L9.049 11.9a1.5 1.5 0 0 1 .906-.014l4.09 1.228a1.5 1.5 0 0 0 .906-.014l2.075-.692A1.5 1.5 0 0 1 19 13.831v3.838a1.5 1.5 0 0 1-1.026 1.423L14.951 20.1a1.5 1.5 0 0 1-.906.014l-4.09-1.228a1.5 1.5 0 0 0-.906.014l-2.075.692A1.5 1.5 0 0 1 5 18.169v-3.838a1.5 1.5 0 0 1 1.026-1.423M9.5 11.75v7m5-5.5v7");
}

</style>
