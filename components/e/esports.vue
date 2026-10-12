<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tjkpv95km"/><path class="u_ss2j5bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:esports" /></template>
<style>
.tjkpv95km {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.15v-4.3q0-.6.44-.2l1.87 1.7q.44.4.85-.04l1.93-2.12q.41-.44.82 0l1.93 2.12q.41.44.85.04l1.87-1.7q.44-.4.44.2v4.3q0 .6-.6.6H7.1q-.6 0-.6-.6M8 11h8a3.5 3.5 0 0 1 3.45 2.9l.6 3.75a2.25 2.25 0 0 1-3.85 1.95L15 18.25H9L7.8 19.6a2.25 2.25 0 0 1-3.85-1.95l.6-3.75A3.5 3.5 0 0 1 8 11m-1.25 3.75h2.5M8 13.5V16");
}

.u_ss2j5bs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 14.25h.01M16.75 16h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
