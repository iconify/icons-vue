<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vfo57uyzf"/><path class="q2fp4ccin"/><path class="p-6zwabto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:byte-pair-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-6zwabto {
  d: path("M6 14v3h12v-3");
}

.q2fp4ccin {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vfo57uyzf {
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
