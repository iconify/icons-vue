<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g4_qklztr"/><path class="i2y7drb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iftar-plate" /></template>
<style>
.g4_qklztr {
  cx: 8.5px;
  cy: 12px;
  r: 5.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2y7drb3d {
  d: path("M8.9 8.92a2.1 1.1-35 1 0-3.44 2.41A2.1 1.1-35 1 0 8.9 8.92m2.64 3.76a2.1 1.1-35 1 0-3.44 2.41a2.1 1.1-35 1 0 3.44-2.41M17.6 6.5h3.05q.6 0 .57.6l-.44 9.8q-.03.6-.63.6H18.1q-.6 0-.63-.6l-.44-9.8q-.03-.6.57-.6m-.45 3h3.95");
}

</style>
