<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mddc0qjct"/><path class="ldj_x1b8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:element-argon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldj_x1b8e {
  d: path("M9.75 10.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 13v4");
}

.mddc0qjct {
  d: path("M9 17c0-2.5-3-4-3-8.5a6 6 0 0 1 12 0c0 4.5-3 6-3 8.5v2.5a3 2 0 0 1-6 0Zm0 0h6");
}

</style>
