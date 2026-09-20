<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0x1wbxg"/><path class="f9v88-bcq"/><path class="pk3q4dmkj"/><path class="mcubrkb2y"/><path class="nood30b4z"/><path class="hort14fyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:account-close-duotone-thin" /></template>
<style>
.f9v88-bcq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hort14fyq {
  d: path("m15 12 -6 6");
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.nood30b4z {
  d: path("m9 12 6 6");
}

.pk3q4dmkj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 12 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yw0x1wbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
