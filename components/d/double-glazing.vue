<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k3_gwo8mx"/><rect class="imr6r1b0w"/><path class="hsr7k9bbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:double-glazing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hsr7k9bbt {
  d: path("m6.25 14.25l3.5-3.5m-3.5 7l6.5-6.5");
}

.imr6r1b0w {
  width: 14px;
  height: 15px;
  x: 2.75px;
  y: 6.25px;
  rx: 2px;
}

.k3_gwo8mx {
  d: path("M6.25 6.25v-1.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2h-2.5");
}

</style>
