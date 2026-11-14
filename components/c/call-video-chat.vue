<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wxoo7k3or"/><path class="k8pbxjbzr"/><path class="z4tw5acrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-video-chat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8pbxjbzr {
  d: path("M9.438 7.5h2.125a2.19 2.19 0 0 1 2.187 2.188v.625a2.19 2.19 0 0 1-2.187 2.187H9.438a2.19 2.19 0 0 1-2.188-2.187v-.625A2.19 2.19 0 0 1 9.438 7.5");
}

.wxoo7k3or {
  d: path("M4 6a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 6v8a2.5 2.5 0 0 1-2.5 2.5H11L7 20v-3.5h-.5A2.5 2.5 0 0 1 4 14Z");
}

.z4tw5acrg {
  d: path("m14.421 8.915l.829-.415a1.036 1.036 0 0 1 1.5.927v1.146a1.036 1.036 0 0 1-1.5.927l-.829-.415A1.21 1.21 0 0 1 13.75 10a1.21 1.21 0 0 1 .671-1.085");
}

</style>
