<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tg8ry4zls"/><path class="r0kksx0xa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bunker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0kksx0xa {
  d: path("M9.5 17v-3a2.5 2.5 0 0 1 5 0v3");
}

.tg8ry4zls {
  d: path("M3.5 17a8.5 9 0 0 1 17 0m-18 0h19");
}

</style>
