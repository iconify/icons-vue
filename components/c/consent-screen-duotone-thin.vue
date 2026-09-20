<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z92okmbgh"/><path class="v7weluf1f"/><path class="jrpnc2pnl"/><path class="hpmnlabtt"/><path class="jfxgqlb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:consent-screen-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpmnlabtt {
  d: path("M6 9h12");
}

.jfxgqlb-n {
  d: path("M8.5 15a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2");
}

.jrpnc2pnl {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.v7weluf1f {
  fill: currentColor;
  d: path("M8.5 15a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z92okmbgh {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
