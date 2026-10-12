<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ayplkabje"/><path class="vm7z00qun"/><path class="g1kxs5bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:for-sale-sign" /></template>
<style>
.ayplkabje {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.75v-9.2q0-1 .78-1.62l5.69-4.55q.78-.63 1.56 0l5.69 4.55q.78.62.78 1.62v.7a7 7 0 0 0-7 7v1.5q0 1-1 1h-5.5q-1 0-1-1");
}

.g1kxs5bwq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 16.25h.01");
}

.vm7z00qun {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.9 14h1.95q.9 0 1.54.64l2.22 2.22q.64.64 0 1.28l-2.47 2.47q-.64.64-1.28 0l-2.22-2.22q-.64-.64-.64-1.54V14.9q0-.9.9-.9");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
