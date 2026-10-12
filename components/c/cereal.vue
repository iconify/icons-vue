<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b23hg9-yy"/><circle class="y1hpw1ytx"/><circle class="c15actb7e"/><circle class="f-2v__buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cereal" /></template>
<style>
.b23hg9-yy {
  d: path("M4 10.75h16a.75.75 0 0 1 .75.8A8.75 8.75 0 0 1 16 18.7v1.55a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V18.7a8.75 8.75 0 0 1-4.75-7.15a.75.75 0 0 1 .75-.8");
}

.c15actb7e {
  cx: 12px;
  cy: 4.5px;
  r: 1.5px;
}

.f-2v__buq {
  cx: 17.75px;
  cy: 6.25px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1hpw1ytx {
  cx: 6.25px;
  cy: 6.25px;
  r: 1.5px;
}

</style>
