<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jv6etml0e"/><path class="ibmegib5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinder-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibmegib5f {
  d: path("M7 7h1.75a1.5 1.5 0 0 1 1.5 1.5v1.75a1.5 1.5 0 0 1-1.5 1.5H7a1.5 1.5 0 0 1-1.5-1.5V8.5A1.5 1.5 0 0 1 7 7m8.25 0H17a1.5 1.5 0 0 1 1.5 1.5v1.75a1.5 1.5 0 0 1-1.5 1.5h-1.75a1.5 1.5 0 0 1-1.5-1.5V8.5a1.5 1.5 0 0 1 1.5-1.5");
}

.jv6etml0e {
  d: path("M4.25 4h15.5a1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 19.75 20H4.25a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 4.25 4M2.5 14.5h19");
}

</style>
