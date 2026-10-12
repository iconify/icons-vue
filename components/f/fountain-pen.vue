<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bx3129b_b"/><path class="mvxg8s0kw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fountain-pen" /></template>
<style>
.bx3129b_b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.49 4.74l1.77 1.77q1.24 1.24 0 2.48l-4.52 4.52q-1.24 1.24-2.48 0l-1.77-1.77q-1.24-1.24 0-2.48l4.52-4.52q1.24-1.24 2.48 0M7.03 11.78l3.69 3.69q.53.53.11 1.15l-1.16 1.76q-.42.62-1.13.85l-4.83 1.54q-.71.23-.48-.48l1.54-4.83q.23-.71.53-1.4l.9-2.12q.3-.69.83-.16");
}

.mvxg8s0kw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 16.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
