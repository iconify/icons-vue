<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0zysybda"/><path class="r8xesg24s"/><path class="xao2ebc6f"/><path class="tb3edh0qa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-last-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0zysybda {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r8xesg24s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tb3edh0qa {
  d: path("m5 5 7 7 -7 7");
}

.xao2ebc6f {
  d: path("M21 5v14");
}

</style>
