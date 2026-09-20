<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6an06b6t"/><path class="h03wmtogt"/><path class="qqgeilbfw"/><path class="usuo56bje"/><path class="ycdy25h0m"/><path class="tt7ypiikb"/><path class="zgod0v2rr"/><path class="du3agkbjb"/><path class="objyy5b5b"/><path class="r2dk7difb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-branch-add-duotone-thin" /></template>
<style>
.du3agkbjb {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h03wmtogt {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.objyy5b5b {
  d: path("M17 9v6");
}

.p6an06b6t {
  fill: currentColor;
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qqgeilbfw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r2dk7difb {
  d: path("M14 12h6");
}

.tt7ypiikb {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.usuo56bje {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ycdy25h0m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgod0v2rr {
  d: path("M7 8.5v7");
}

</style>
