<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxpjp6bds"/><circle class="jrypmlbrb"/><path class="o3jrfrb2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:french-horn" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrypmlbrb {
  cx: 9.5px;
  cy: 11px;
  r: 3.75px;
}

.o3jrfrb2t {
  d: path("M12.5 17c4 0 6.5-1.25 8.25-3.5V21c-1.75-1.5-4.25-2.5-8.25-2.5Z");
}

.qxpjp6bds {
  d: path("M18.5 4.25h-9A6.75 6.75 0 0 0 2.75 11a6.75 6.75 0 0 0 6.75 6.75h3m6-15v3");
}

</style>
