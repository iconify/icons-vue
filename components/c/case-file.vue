<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="woebuvcnq"/><rect class="ew1rf9pnm"/><path class="w0sebyb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:case-file" /></template>
<style>
.ew1rf9pnm {
  width: 10.5px;
  height: 5px;
  x: 6.75px;
  y: 11px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w0sebyb3m {
  d: path("M9 13.5h6");
}

.woebuvcnq {
  d: path("M2.75 6.75a2 2 0 0 1 2-2h4l2 2.25h8.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Z");
}

</style>
