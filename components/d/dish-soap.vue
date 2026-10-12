<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eixp8sb5w"/><path class="urjkyporg"/><path class="ujk2d4bbq"/><circle class="hxly0r3mq"/><circle class="prxayub-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dish-soap" /></template>
<style>
.eixp8sb5w {
  width: 3.5px;
  height: 4px;
  x: 10.25px;
  y: 4.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxly0r3mq {
  cx: 18.75px;
  cy: 4.75px;
  r: 1.75px;
}

.prxayub-e {
  cx: 5.5px;
  cy: 4.25px;
  r: 1.25px;
}

.ujk2d4bbq {
  d: path("M12 12.25c1 1.15 1.5 2 1.5 2.65a1.5 1.5 0 0 1-3 0c0-.65.5-1.5 1.5-2.65");
}

.urjkyporg {
  d: path("M8.25 8.25h7.5a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-7.5a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2");
}

</style>
