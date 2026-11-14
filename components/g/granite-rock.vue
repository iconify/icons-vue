<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abxc-bbri"/><path class="clmrij5rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:granite-rock" /></template>
<style>
.abxc-bbri {
  d: path("m2.668 14.496l2.18-6.54a1.5 1.5 0 0 1 .541-.739l4.569-3.323a1.5 1.5 0 0 1 1.197-.254l5.718 1.226a1.5 1.5 0 0 1 .963.68l3.333 5.416a1.5 1.5 0 0 1 .178 1.15l-1.596 6.383a1.5 1.5 0 0 1-1.28 1.126l-7.224.85a1.5 1.5 0 0 1-.49-.023l-5.955-1.276a1.5 1.5 0 0 1-1.09-.94l-1.026-2.735a1.5 1.5 0 0 1-.018-1.001");
}

.clmrij5rf {
  d: path("m10.5 3.5l2.5 6l8.5 2M7 12.5h.01M11.5 16h.01m4.99-1h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
