<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ey2jx2ehi"/><path class="wev624bkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hypermarket" /></template>
<style>
.ey2jx2ehi {
  d: path("m3 7l1-4h16l1 4M3.5 9.5v12h17v-12M3 7a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0a1.5 1.5 0 0 0 3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wev624bkl {
  d: path("M7.5 12.5h9A1.5 1.5 0 0 1 18 14v6a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 20v-6a1.5 1.5 0 0 1 1.5-1.5m2.5 0v9m4-9v9");
}

</style>
