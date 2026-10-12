<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="unt8_q5bx"/><path class="nlndkkbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:digging-worker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlndkkbfb {
  d: path("m7.5 8l2 6m0 0L7 21.25M9.5 14l3.5 2.5v4.75m-5-12l5.25 2m-1.75-3L17.25 17m-.95.62l1.9-1.24q.5-.33.6.26l.55 3.12q.1.59-.4.26l-2.65-1.74q-.5-.33 0-.66");
}

.unt8_q5bx {
  cx: 6.5px;
  cy: 4.75px;
  r: 2px;
}

</style>
