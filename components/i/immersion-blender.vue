<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiknqcb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:immersion-blender" /></template>
<style>
.yiknqcb0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za2.75 2.75 0 0 1 2.75 2.75v4A2.75 2.75 0 0 1 12 12a2.75 2.75 0 0 1-2.75-2.75v-4A2.75 2.75 0 0 1 12 2.5m0 9.5v3.5m-5.5 6v-2a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v2Zm5.5-16v2");
}

</style>
