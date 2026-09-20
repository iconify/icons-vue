<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgcyabcdk"/><path class="v_45uabpq"/><path class="sbiy6014w"/><path class="c46fyy1pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fallback-duotone-thin" /></template>
<style>
.c46fyy1pe {
  d: path("m16 12 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgcyabcdk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h9v8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sbiy6014w {
  d: path("M3 7h9v8h7");
}

.v_45uabpq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
