<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ko01rhb0b"/><circle class="jb8wwbf-o"/><path class="jv4lm2xpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb8wwbf-o {
  cx: 12px;
  cy: 10px;
  r: 1.25px;
}

.jv4lm2xpl {
  d: path("M12 11.25c3 3 4 4.5 4 6a4 4 0 0 1-8 0c0-1.5 1-3 4-6");
}

.ko01rhb0b {
  d: path("M9.75 5.25a2.25 2.25 0 1 1 4.5 0C14.25 6.75 12 7 12 8.75");
}

</style>
