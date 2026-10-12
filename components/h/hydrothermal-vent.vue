<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ielwpzbbm"/><path class="m9ir5cbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydrothermal-vent" /></template>
<style>
.ielwpzbbm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.16 20.52l2.18-9.79q.16-.73.91-.73h3.5q.75 0 .91.73l2.18 9.79q.16.73-.59.73h-8.5q-.75 0-.59-.73m3.34-5.02h3M2.75 21.25h18.5");
}

.m9ir5cbdc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 6.5h.01m2.49-3.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
