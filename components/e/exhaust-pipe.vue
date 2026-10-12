<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kv8x6cpfx"/><path class="xj24ni17m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:exhaust-pipe" /></template>
<style>
.kv8x6cpfx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12H14q.75 0 1.33-.48l.34-.29q.58-.48.58.27v6q0 .75-.58.27l-.34-.29Q14.75 17 14 17H3.5q-.75 0-.75-.75v-3.5q0-.75.75-.75m3 5v3");
}

.xj24ni17m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 14.5h.01m-.51-5h.01M16 5.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
