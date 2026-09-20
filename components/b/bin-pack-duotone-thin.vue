<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5iyf-xsj"/><path class="oiw0w4bmy"/><path class="qe97cg-lx"/><path class="hsljpwbfc"/><path class="j2iebkbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bin-pack-duotone-thin" /></template>
<style>
.g5iyf-xsj {
  fill: currentColor;
  d: path("M6 13.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
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

.hsljpwbfc {
  d: path("M6 13.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.j2iebkbix {
  d: path("M15.5 16a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2");
}

.oiw0w4bmy {
  fill: currentColor;
  d: path("M15.5 16a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

</style>
