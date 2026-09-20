<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="et8xb5bpy"/><path class="mzkwo-z2x"/><path class="zqac8xasw"/><path class="mxb6569jn"/><path class="m0hesomws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gamepad-outline-thin" /></template>
<style>
.et8xb5bpy {
  d: path("M2 12a5.5 5.5 0 0 1 5.5 -5.5h9A5.5 5.5 0 0 1 22 12a5.5 5.5 0 0 1 -5.5 5.5h-9A5.5 5.5 0 0 1 2 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0hesomws {
  d: path("M18 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mxb6569jn {
  d: path("M15 10.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mzkwo-z2x {
  d: path("M7 9.5v5");
}

.zqac8xasw {
  d: path("M4.5 12h5");
}

</style>
