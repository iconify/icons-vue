<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9lzy9btx"/><path class="bmpppjasm"/><path class="isvgtub8p"/><path class="xpi-ctm3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-down-right-duotone-thin" /></template>
<style>
.bmpppjasm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isvgtub8p {
  d: path("M4 4v10h16");
}

.s9lzy9btx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xpi-ctm3k {
  d: path("m15 9 5 5 -5 5");
}

</style>
