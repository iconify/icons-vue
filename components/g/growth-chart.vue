<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cloq1fb7n"/><path class="y59ex3bht"/><circle class="r9-7jjbjg"/><path class="r6bu50dmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:growth-chart" /></template>
<style>
.cloq1fb7n {
  width: 6px;
  height: 18.5px;
  x: 4px;
  y: 2.75px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6bu50dmx {
  d: path("M12.5 21.25v-4a3.25 3.25 0 0 1 6.5 0v4Z");
}

.r9-7jjbjg {
  cx: 15.75px;
  cy: 9.5px;
  r: 2px;
}

.y59ex3bht {
  d: path("M4 6.5h2.5M4 10h3.5M4 13.5h2.5M4 17h3.5M10 5h8.75");
}

</style>
