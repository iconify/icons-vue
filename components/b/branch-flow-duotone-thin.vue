<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ac2e6i0cq"/><path class="ogeh55o6v"/><path class="uol1biies"/><path class="q9br621tu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:branch-flow-duotone-thin" /></template>
<style>
.ac2e6i0cq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h7l5 -5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogeh55o6v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 5 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q9br621tu {
  d: path("m9 12 5 5h8");
}

.uol1biies {
  d: path("M2 12h7l5 -5h8");
}

</style>
