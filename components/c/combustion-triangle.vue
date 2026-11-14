<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b70zeobbc"/><path class="knbykxt6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:combustion-triangle" /></template>
<style>
.b70zeobbc {
  d: path("m14.277 6.47l5.218 9.099a2.625 2.625 0 0 1-2.277 3.931H6.782a2.625 2.625 0 0 1-2.277-3.931L9.723 6.47a2.625 2.625 0 0 1 4.554 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knbykxt6b {
  d: path("M12.75 8.5c.25 2 2.25 3 2.25 5.5a3.5 3.5 0 0 1-6 0c0-1.5 1-2.5 1.75-2.75c0 1 .5 1.5 1 1.5c.25-1.75 1-2.75 1-4.25");
}

</style>
