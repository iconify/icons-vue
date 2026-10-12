<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nhfx1zb1g"/><path class="hisr-d3nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:garage-remote" /></template>
<style>
.hisr-d3nd {
  d: path("M6.75 21.25v-8.5a1 1 0 0 1 1-1h8.5a1 1 0 0 1 1 1v8.5M8.75 15h6.5m-6.5 3.25h6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhfx1zb1g {
  d: path("M2.75 9L12 3.25L21.25 9v10.25a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Z");
}

</style>
