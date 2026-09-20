<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jn0gqvt5f"/><path class="f71-6vaey"/><path class="jw0risdcq"/><path class="j6xe62btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunk-overlap-duotone-thin" /></template>
<style>
.f71-6vaey {
  fill: currentColor;
  d: path("M8 15.5a2.5 2.5 0 0 1 2.5 -2.5h8a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 8 15.5");
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

.j6xe62btt {
  d: path("M8 15.5a2.5 2.5 0 0 1 2.5 -2.5h8a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 8 15.5");
}

.jn0gqvt5f {
  fill: currentColor;
  d: path("M3 7.5A2.5 2.5 0 0 1 5.5 5h8A2.5 2.5 0 0 1 16 7.5a2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 3 7.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jw0risdcq {
  d: path("M3 7.5A2.5 2.5 0 0 1 5.5 5h8A2.5 2.5 0 0 1 16 7.5a2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 3 7.5");
}

</style>
