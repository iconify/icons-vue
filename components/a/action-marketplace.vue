<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwsbsnbrg"/><path class="wqoekub6e"/><path class="n4o71kbzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:action-marketplace" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4o71kbzb {
  d: path("M8 20.5V15h4v5.5m5.717-5.691l-1.788 2.264a.727.727 0 0 0 .571 1.177a1.08 1.08 0 0 1 1.026 1.423l-.151.452a.358.358 0 0 0 .619.339l2.062-2.548a.716.716 0 0 0-.556-1.166a1.193 1.193 0 0 1-1.163-1.462l.038-.163a.374.374 0 0 0-.658-.316");
}

.wqoekub6e {
  d: path("M5 10v10.5h9.5M19 12v-2");
}

.wwsbsnbrg {
  d: path("m3.5 8l2-4.5h13l2 4.5a2.125 2.125 0 0 1-4.25 0A2.125 2.125 0 0 1 12 8a2.125 2.125 0 0 1-4.25 0A2.125 2.125 0 0 1 3.5 8");
}

</style>
