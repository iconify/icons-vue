<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p6o5yfb-l"/><path class="k9pk4ac0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magic-wand" /></template>
<style>
.k9pk4ac0w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.25 17h.01");
}

.p6o5yfb-l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 20.25l8-8m5-9.5q.54 3.96 4.5 4.5q-3.96.54-4.5 4.5q-.54-3.96-4.5-4.5q3.96-.54 4.5-4.5m-10.25 2v3.5M4.75 6.5h3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
