<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8jhv79aa"/><path class="hkh8hr_1w"/><path class="mu5pjkbqo"/><path class="spi9wczkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-board-duotone-thin" /></template>
<style>
.e8jhv79aa {
  fill: currentColor;
  d: path("M3 3v18h18V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hkh8hr_1w {
  fill: currentColor;
  d: path("M8 8v8h8V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu5pjkbqo {
  d: path("M3 3v18h18V3Z");
}

.spi9wczkf {
  d: path("M8 8v8h8V8Z");
}

</style>
