<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnq0mhbyd"/><circle class="g8q59cbpc"/><path class="fk-vzub7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:best-seller" /></template>
<style>
.fk-vzub7b {
  d: path("m14.64 8.67l.82 1.84q.15.32.49.36l2.01.21q.34.03.08.27l-1.49 1.35q-.26.23-.19.57l.42 1.97q.07.35-.23.17L14.8 14.4q-.3-.17-.6 0l-1.75 1.01q-.3.18-.23-.17l.42-1.97q.07-.34-.19-.57l-1.49-1.35q-.26-.24.08-.27l2.01-.21q.34-.04.49-.36l.82-1.84q.14-.32.28 0");
}

.g8q59cbpc {
  cx: 7.5px;
  cy: 12px;
  r: 1.1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnq0mhbyd {
  d: path("M8.66 5.75h10.59a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2H8.66a2 2 0 0 1-1.48-.66l-3.86-4.25a2 2 0 0 1 0-2.68l3.86-4.25a2 2 0 0 1 1.48-.66");
}

</style>
