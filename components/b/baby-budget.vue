<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmdoce30z"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-budget" /></template>
<style>
.fmdoce30z {
  d: path("M7.25 6.25v-1.5a2 2 0 0 1 4 0v1.5m-7 0h10A1.25 1.25 0 0 1 15.5 7.5a1.25 1.25 0 0 1-1.25 1.25h-10A1.25 1.25 0 0 1 3 7.5a1.25 1.25 0 0 1 1.25-1.25m-.75 2.5V19q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T6 21.5h6.423M15 12.504V8.75M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

</style>
