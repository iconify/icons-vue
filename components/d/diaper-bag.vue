<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwx_40u5s"/><path class="oxg6of9kb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diaper-bag" /></template>
<style>
.cwx_40u5s {
  d: path("M4 9h16l-1 11a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 20Zm2.5 0V5.5a2 2 0 0 1 4 0V9m3 0V5.5a2 2 0 0 1 4 0V9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oxg6of9kb {
  d: path("M10.5 13.5h3A2.5 2.5 0 0 1 16 16a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 8 16a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
