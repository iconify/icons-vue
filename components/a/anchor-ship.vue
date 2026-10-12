<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="plq-ic0hl"/><path class="tru4xo21p"/><circle class="t88z8mbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anchor-ship" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.plq-ic0hl {
  d: path("M2.75 10.5C4.5 8.5 5.25 5.75 5 2.75m7 3.5V21M8.25 9h7.5M5.5 12.75H3.75a8.25 8.25 0 0 0 16.5 0H18.5");
}

.t88z8mbby {
  cx: 12px;
  cy: 4.5px;
  r: 1.75px;
}

.tru4xo21p {
  d: path("M10.25 4Q7.625 2.875 5 5.5");
}

</style>
