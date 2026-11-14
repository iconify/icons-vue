<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lcg02sl1z"/><path class="hwwfw6bzu"/><path class="l8p5bbb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ct-scanner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwwfw6bzu {
  d: path("m5 15l-1 6.5h10L13 15m-7-5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.l8p5bbb1t {
  d: path("M10 9h10.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1a1 1 0 0 1 1-1m8.5 2v10.5");
}

.lcg02sl1z {
  d: path("M2.5 10a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

</style>
