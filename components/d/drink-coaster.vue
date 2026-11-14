<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fblnu-b5k"/><path class="j3320rbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drink-coaster" /></template>
<style>
.fblnu-b5k {
  d: path("M7.5 13a9.5 3.5 0 0 0-5 3a9.5 3.5 0 0 0 19 0a9.5 3.5 0 0 0-6-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3320rbat {
  d: path("M7.5 4h8v9.5A2.5 2.5 0 0 1 13 16h-3a2.5 2.5 0 0 1-2.5-2.5Zm8 2h.5a2.25 2.25 0 0 1 0 4.5h-.5");
}

</style>
