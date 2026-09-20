<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z6y0gfbug"/><path class="a-v3knb-a"/><path class="qgw5bw59f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cash-register-outline-thin" /></template>
<style>
.a-v3knb-a {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qgw5bw59f {
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z6y0gfbug {
  d: path("M7 4.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V7a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
