<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byg9qhb1x"/><path class="e-hz86dqn"/><path class="xlsprdnsf"/><path class="rrb5igeqn"/><path class="g9v3j3igs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:benchmark-code-outline-thin" /></template>
<style>
.byg9qhb1x {
  d: path("M3 13a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.e-hz86dqn {
  d: path("m10 13 4 -4");
}

.g9v3j3igs {
  d: path("M22 6v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rrb5igeqn {
  d: path("M19 4v4");
}

.xlsprdnsf {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
