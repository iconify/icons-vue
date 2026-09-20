<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuygslbyc"/><path class="e7pgrp-wx"/><path class="lrtehacrs"/><path class="nubd6obsf"/><path class="a8_u4qbvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:encrypt-duotone-thin" /></template>
<style>
.a8_u4qbvt {
  d: path("M14 10a3 3 0 0 1 6 0");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrtehacrs {
  d: path("m6 9 3 3 -3 3");
}

.nubd6obsf {
  d: path("M12 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

.tuygslbyc {
  fill: currentColor;
  d: path("M12 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
