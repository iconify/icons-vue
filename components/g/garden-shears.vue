<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s7om7zyhk"/><path class="xfr5p399b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-shears" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s7om7zyhk {
  d: path("M8 2.5q.5 5 4 7.25l2 2.75");
}

.xfr5p399b {
  d: path("M16 2.5q-.5 5-4 7.25l-2 2.75m.081.064za1.75 1.75 0 0 1 .43 2.437l-3.155 4.505a1.75 1.75 0 0 1-2.437.43a1.75 1.75 0 0 1-.43-2.437l3.155-4.505a1.75 1.75 0 0 1 2.437-.43m3.838 0za1.75 1.75 0 0 1 2.437.43l3.155 4.505a1.75 1.75 0 0 1-.43 2.437a1.75 1.75 0 0 1-2.437-.43l-3.155-4.505a1.75 1.75 0 0 1 .43-2.437M12 9.75h.01");
}

</style>
