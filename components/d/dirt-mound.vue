<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yfl9_1b4e"/><path class="d9c9_9b1w"/><path class="z_9qi1hcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dirt-mound" /></template>
<style>
.d9c9_9b1w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 17h.01m3.99-2h.01M15 17.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yfl9_1b4e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25C3.75 14 7.25 10 12 10s8.25 4 9.25 10.25Z");
}

.z_9qi1hcx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 10.75v-6.5m-1.5 0h3");
}

</style>
