<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l51r-wb3s"/><path class="z7wppxt9k"/><path class="ce80bno8x"/><path class="q8wiyhb5n"/><path class="szshe-6ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chore-list-duotone-thin" /></template>
<style>
.ce80bno8x {
  d: path("M9 5V2h6v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l51r-wb3s {
  fill: currentColor;
  d: path("M4 5v16h16V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q8wiyhb5n {
  d: path("m7 11 2 2 4 -4");
}

.szshe-6ah {
  d: path("M7 17h10");
}

.z7wppxt9k {
  d: path("M4 5v16h16V5Z");
}

</style>
