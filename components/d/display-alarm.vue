<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_ni2v0op"/><path class="x-kj8rb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:display-alarm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_ni2v0op {
  d: path("m13.374 3.005l2.093.369a2.19 2.19 0 0 1 1.774 2.535l-1.324 7.509a2.19 2.19 0 0 1-2.534 1.774l-2.093-.369a2.19 2.19 0 0 1-1.774-2.534L10.84 4.78a2.19 2.19 0 0 1 2.534-1.775M6.5 17v1.75a5.5 2 0 0 0 11 0V17");
}

.x-kj8rb-n {
  d: path("M6.5 17a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0m7.776-11.551h.01M6.371 11.75a6.5 6.5 0 0 1 0-6.5m11.258 0a6.5 6.5 0 0 1 0 6.5m-14.012.659a9.25 9.25 0 0 1 0-7.818m16.766 0a9.25 9.25 0 0 1 0 7.818");
}

</style>
