<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g828vzbqg"/><rect class="z_o25m1pf"/><path class="j2xg21cof"/><path class="cyy3ax33u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candidate-podium" /></template>
<style>
.cyy3ax33u {
  d: path("m12.14 15.07l.34.76q.14.32.49.36l.82.08q.35.03.09.27l-.62.55q-.26.23-.19.58l.18.81q.07.34-.23.16l-.72-.41q-.3-.18-.6 0l-.72.41q-.3.18-.23-.16l.18-.81q.07-.35-.19-.58l-.62-.55q-.26-.24.09-.27l.82-.08q.35-.04.49-.36l.34-.76q.14-.32.28 0");
}

.g828vzbqg {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2xg21cof {
  d: path("M7.25 12.25h9.5v8a1 1 0 0 1-1 1h-7.5a1 1 0 0 1-1-1Z");
}

.z_o25m1pf {
  width: 15.5px;
  height: 2.5px;
  x: 4.25px;
  y: 9.75px;
  rx: 1px;
}

</style>
