<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh7bbcc6l"/><path class="nr7ye601t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-handle-lever" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr7ye601t {
  d: path("M10.25 6.5zA1.75 1.75 0 0 1 12 8.25v7.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-7.5a1.75 1.75 0 0 1 1.75-1.75m1.75 3h7.5a1.5 1.5 0 0 1 0 3H12");
}

.yh7bbcc6l {
  d: path("M5.625 2.5h7.25A2.625 2.625 0 0 1 15.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625h-7.25A2.625 2.625 0 0 1 3 18.875V5.125A2.625 2.625 0 0 1 5.625 2.5");
}

</style>
