<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hq7q5pbzv"/><path class="m690iuuio"/><path class="khupvdbel"/><path class="x7qdjyb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:corner-left-down-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hq7q5pbzv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4H10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khupvdbel {
  d: path("M20 4H10v16");
}

.m690iuuio {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7qdjyb5k {
  d: path("m5 15 5 5 5 -5");
}

</style>
