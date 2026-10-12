<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l0a6x-kur"/><circle class="gpj5lihjv"/><path class="h61rhn2jc"/><path class="pvi3c1b4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cathedral" /></template>
<style>
.gpj5lihjv {
  cx: 12px;
  cy: 12.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.h61rhn2jc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25v-2.5a1.75 1.75 0 0 1 3.5 0v2.5");
}

.l0a6x-kur {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V8.6q0-.6.22-1.16l1.56-3.88q.22-.56.44 0l1.56 3.88q.22.56.22 1.16v1.8q0 .6.49.25l4.27-3.05q.49-.35.98 0l4.27 3.05q.49.35.49-.25V8.6q0-.6.22-1.16l1.56-3.88q.22-.56.44 0l1.56 3.88q.22.56.22 1.16v12.05q0 .6-.6.6H3.35q-.6 0-.6-.6");
}

.pvi3c1b4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 12.5h.01m14.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
