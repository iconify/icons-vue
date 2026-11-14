<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxsen4opx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audio-falloff" /></template>
<style>
.qxsen4opx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.5h1.578a1.75 1.75 0 0 0 1.171-.449L9.5 5.25A1.498 1.498 0 0 1 12 6.363v8.274a1.498 1.498 0 0 1-2.5 1.113l-2.001-1.801a1.75 1.75 0 0 0-1.171-.449H4.75A1.75 1.75 0 0 1 3 11.75v-2.5A1.75 1.75 0 0 1 4.75 7.5M15 7.5q2 3 0 6M17.75 5q2.244 3.526 1.611 7.052M18 14.5v7m-3-3l3 3l3-3");
}

</style>
