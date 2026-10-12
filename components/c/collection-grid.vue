<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rbx896b-y"/><rect class="t8j_wib_h"/><rect class="lkve0tb3s"/><path class="t88ghul1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:collection-grid" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkve0tb3s {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 2px;
}

.rbx896b-y {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.t88ghul1m {
  d: path("M14.75 14.5A1.25 1.25 0 0 1 16 13.25h3.5a1.25 1.25 0 0 1 1.25 1.25v6.1c0 .5-.55.75-.95.5l-2.05-1.5l-2.05 1.5c-.4.25-.95 0-.95-.5Z");
}

.t8j_wib_h {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 2.75px;
  rx: 2px;
}

</style>
