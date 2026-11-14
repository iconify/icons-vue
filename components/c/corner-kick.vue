<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ubgs56bfy"/><path class="uc41nmbar"/><path class="s9os3nb7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corner-kick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s9os3nb7h {
  fill: currentColor;
  d: path("m13.9 11.675l.235.176a1.5 1.5 0 0 1 .523 1.675l-.066.198a1.5 1.5 0 0 1-1.423 1.026h-.338a1.5 1.5 0 0 1-1.423-1.026l-.066-.198a1.5 1.5 0 0 1 .523-1.675l.235-.176a1.5 1.5 0 0 1 1.8 0");
}

.ubgs56bfy {
  d: path("M21.5 3v18.5H3");
}

.uc41nmbar {
  d: path("M17.5 21.5a4 4 0 0 1 4-4M8 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
