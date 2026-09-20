<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtpp5wbuo"/><path class="vryjydbyu"/><path class="igshzyi-w"/><path class="i0gx68gak"/><path class="m27ljac1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:approve-step-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0gx68gak {
  d: path("M14 12h4");
}

.igshzyi-w {
  d: path("m5 12 2 2 3.5 -3.5");
}

.m27ljac1c {
  d: path("m18 9 3 3 -3 3");
}

.mtpp5wbuo {
  fill: currentColor;
  d: path("M2 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vryjydbyu {
  d: path("M2 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
