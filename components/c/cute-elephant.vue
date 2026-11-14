<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0j8q4b6d"/><path class="s_c3qlbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-elephant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_c3qlbrk {
  d: path("M12.5 4.5c-2.75 1.5-2.75 8.25 1 8.25c3 0 4-3.75 3.25-8.25m-8.5 5.25h.01");
}

.v0j8q4b6d {
  d: path("M6.5 10c0-3.5 2.5-5.5 6-5.5h4c3 0 5 2.5 5 6v9H18V16h-4.5v3.5H10v-5c-2.5 0-3.25 2-3.25 4.25a1.75 1.75 0 0 1-3.5 0C3.25 15 4.5 12.5 6.5 10");
}

</style>
