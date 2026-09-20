<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4kv94yfp"/><path class="cf-dqybgk"/><path class="duxy6wbvl"/><path class="ok9ioqb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:groundedness-duotone-thin" /></template>
<style>
.cf-dqybgk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.duxy6wbvl {
  d: path("m7 9 4 4 6 -6");
}

.f4kv94yfp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 9 4 4 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

</style>
