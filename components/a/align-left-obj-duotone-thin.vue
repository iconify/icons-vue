<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o60er10sa"/><path class="tmq95o5-h"/><path class="rcsjgin3k"/><path class="s0n4kcc4d"/><path class="uw5kuce7r"/><path class="j41x8568l"/><path class="zdse1fb0u"/><path class="cfq8fpb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-left-obj-duotone-thin" /></template>
<style>
.cfq8fpb9k {
  d: path("M5.5 17H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j41x8568l {
  d: path("M5.5 7H15");
}

.o60er10sa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rcsjgin3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 12H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0n4kcc4d {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 17H12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tmq95o5-h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 7H15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.zdse1fb0u {
  d: path("M5.5 12H19");
}

</style>
