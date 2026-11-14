<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwozeg7ww"/><path class="c5nup6bhu"/><path class="t4qxwab-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gauge-medium" /></template>
<style>
.c5nup6bhu {
  fill: currentColor;
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4qxwab-a {
  d: path("M12 14V8.25M15 18h6");
}

.wwozeg7ww {
  d: path("M3 14a9 9 0 0 1 18 0");
}

</style>
