<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tgbcy_2pb"/><path class="h8y6kwivj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conversation-branch" /></template>
<style>
.h8y6kwivj {
  d: path("M18 11v1a3.5 3.5 0 0 1-3.5 3.5H6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tgbcy_2pb {
  d: path("M4 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0M16 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0M6 7.5v9");
}

</style>
