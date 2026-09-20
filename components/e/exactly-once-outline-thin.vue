<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlt4pubuu"/><path class="iedujiqkb"/><path class="fotxf46ll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exactly-once-outline-thin" /></template>
<style>
.fotxf46ll {
  d: path("m14 12.5 3 3 4.5 -4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jlt4pubuu {
  d: path("M4 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
