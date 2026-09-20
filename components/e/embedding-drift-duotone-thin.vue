<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8o2etigh"/><path class="ohnyu1eql"/><path class="h1f2yzbjx"/><path class="srf482-ro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:embedding-drift-duotone-thin" /></template>
<style>
.d8o2etigh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h1f2yzbjx {
  d: path("M8.5 5 11 7.5l-4 4 -4 -4L5.5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohnyu1eql {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 14 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.srf482-ro {
  d: path("m10 14 3 3 3 -3 3 3");
}

</style>
