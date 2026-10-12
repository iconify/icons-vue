<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="b77aqib7z"/><path class="ucai-vb8d"/><path class="ep7oof8hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confused" /></template>
<style>
.b77aqib7z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.75c.75-.5 1.75-.5 2.5 0m4 0L16.5 7");
}

.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ep7oof8hh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16.5c1-1 2-.25 3-.75s2-1 3-.25");
}

.ucai-vb8d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01M15 10h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
