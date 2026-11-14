<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b__wpqzxp"/><path class="nyb76tj1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bot-sad" /></template>
<style>
.b__wpqzxp {
  d: path("M10.25 7h3.5a6.75 6.75 0 0 1 6.75 6.75a6.75 6.75 0 0 1-6.75 6.75h-3.5a6.75 6.75 0 0 1-6.75-6.75A6.75 6.75 0 0 1 10.25 7M12 2.5V7m-3.5 6.5h.01m6.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyb76tj1k {
  d: path("M10 18c1-1.5 3-1.5 4 0");
}

</style>
