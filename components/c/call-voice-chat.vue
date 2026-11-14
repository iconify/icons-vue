<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wxoo7k3or"/><path class="p80ubdbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-voice-chat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p80ubdbfg {
  d: path("M10.5 6.5c.25 0 .5.25.75.5l.25 1.25c0 .25 0 .5-.25.75l-.75.25c.5 1.25 1 1.75 2.25 2.25l.25-.75c.25-.25.5-.25.75-.25l1.25.25c.25.25.5.5.5.75v1.25q0 .75-.75.75c-3.5 0-6.25-2.75-6.25-6.25q0-.75.75-.75Z");
}

.wxoo7k3or {
  d: path("M4 6a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 6v8a2.5 2.5 0 0 1-2.5 2.5H11L7 20v-3.5h-.5A2.5 2.5 0 0 1 4 14Z");
}

</style>
