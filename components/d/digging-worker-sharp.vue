<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="unt8_q5bx"/><path class="zfaw3dzzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:digging-worker-sharp" /></template>
<style>
.unt8_q5bx {
  cx: 6.5px;
  cy: 4.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfaw3dzzr {
  d: path("m7.5 8l2 6m0 0L7 21.25M9.5 14l3.5 2.5v4.75m-5-12l5.25 2m-1.75-3L17.25 17m-.95.62l1.9-1.24l.5-.33l.1.59l.55 3.12l.1.59l-.5-.33l-2.65-1.74l-.5-.33z");
}

</style>
