<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxz-oicoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:core-network" /></template>
<style>
.yxz-oicoe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.625 9h.75A2.625 2.625 0 0 1 15 11.625v.75A2.625 2.625 0 0 1 12.375 15h-.75A2.625 2.625 0 0 1 9 12.375v-.75A2.625 2.625 0 0 1 11.625 9M4.5 2.5a2 2 0 1 0 0 4a2 2 0 1 0 0-4m15 0a2 2 0 1 0 0 4a2 2 0 1 0 0-4m-15 15a2 2 0 1 0 0 4a2 2 0 1 0 0-4m15 0a2 2 0 1 0 0 4a2 2 0 1 0 0-4M6 6l3.5 3.5M18 6l-3.5 3.5M6 18l3.5-3.5M18 18l-3.5-3.5M9 12h6");
}

</style>
