<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx6d6x3hh"/><path class="uxahocbdu"/><path class="esxx8sbse"/><path class="h4gumgb9f"/><path class="gr1zxddav"/><path class="swzjdoakn"/><path class="zm2dyvb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:doorbell-duotone-thin" /></template>
<style>
.esxx8sbse {
  fill: currentColor;
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gr1zxddav {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.h4gumgb9f {
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.swzjdoakn {
  d: path("M11 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uxahocbdu {
  fill: currentColor;
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yx6d6x3hh {
  fill: currentColor;
  d: path("M7 5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zm2dyvb-o {
  d: path("M9 16h6");
}

</style>
