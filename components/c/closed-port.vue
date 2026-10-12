<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ah1ntn79p"/><path class="ni82uqr6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:closed-port" /></template>
<style>
.ah1ntn79p {
  width: 10.5px;
  height: 7.5px;
  x: 6.75px;
  y: 11.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ni82uqr6b {
  d: path("M9 11.75V8a3 3 0 0 1 6 0v3.75m-4.5 2.75v2m3-2v2");
}

</style>
