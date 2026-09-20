<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asgcn6r8p"/><path class="r5stgpb3n"/><path class="v-yh3actq"/><path class="q7kpryb3v"/><path class="a8cyhwbdj"/><path class="rw6ho_bav"/><path class="oc7wmvdee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calendar-run-duotone-thin" /></template>
<style>
.a8cyhwbdj {
  d: path("M16 2v3");
}

.asgcn6r8p {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
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

.oc7wmvdee {
  d: path("m10 12 3 3 -3 3Z");
}

.q7kpryb3v {
  d: path("M8 2v3");
}

.r5stgpb3n {
  fill: currentColor;
  d: path("m10 12 3 3 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.v-yh3actq {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
