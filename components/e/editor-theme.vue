<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f7x0bxb0t"/><path class="i3wq43b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:editor-theme" /></template>
<style>
.f7x0bxb0t {
  d: path("M12 2.5c-5.25 0-9.5 4.25-9.5 9.5s4.25 9.5 9.5 9.5c1.5 0 2-1 2-2c0-1.5-1-2-1-3.25c0-1 .75-1.75 2-1.75h2c2.5 0 4.5-2 4.5-4.5c0-4.25-4.25-7.5-9.5-7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3wq43b6i {
  fill: currentColor;
  d: path("M6.5 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0M8 7.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5-1a1 1 0 1 0 2 0a1 1 0 1 0-2 0m3.5 3a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
