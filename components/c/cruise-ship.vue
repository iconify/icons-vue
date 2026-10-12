<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="a1q4-u_vk"/><path class="oo0y9dcka"/><path class="zdwkkh4ek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cruise-ship" /></template>
<style>
.a1q4-u_vk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.35 9.01l.55-4.27Q10 4 10.75 4h2q.75 0 .85.74l.55 4.27q.1.74-.65.74H10q-.75 0-.65-.74m-5.6 5.24h.5q1 0 1-1v-2.5q0-1 1-1H16.5q1 0 1 1v2.5q0 1 1 1h1.75q1 0 .64.93l-1.78 4.64q-.36.93-1.36.93H6.25q-1 0-1.36-.93l-1.78-4.64q-.36-.93.64-.93");
}

.oo0y9dcka {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12.25h.01m3.49 0h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zdwkkh4ek {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.25h18");
}

</style>
