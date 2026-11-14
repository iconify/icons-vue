<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zcgbq6p2r"/><path class="juv0c-8yk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bed-king" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.juv0c-8yk {
  d: path("M8.25 8.5h.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.75 12h-.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 8.25 8.5m7 0h.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 15.75 12h-.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

.zcgbq6p2r {
  d: path("M3.5 12V5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v7M4.25 12h15.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 19.75 17H4.25a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 4.25 12m.25 5v3.5m15-3.5v3.5");
}

</style>
