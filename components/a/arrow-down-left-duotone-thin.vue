<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ncm8vib4e"/><path class="oo0zq0w3g"/><path class="piaam4vpr"/><path class="i67dqei2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-left-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i67dqei2u {
  d: path("M4 10v10h10");
}

.ncm8vib4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4 4 20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oo0zq0w3g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.piaam4vpr {
  d: path("M20 4 4 20");
}

</style>
