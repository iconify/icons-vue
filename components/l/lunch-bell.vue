<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="juuxvsqpf"/><path class="p_wt0acuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunch-bell" /></template>
<style>
.juuxvsqpf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.88 16.79l1.62 2.84q.5.87-.5.87H5q-1 0-.5-.87l7-12.26q.5-.87 1 0l3.8 6.65M12 2.75a.75.75 0 1 1 0 1.5a.75.75 0 1 1 0-1.5m0 1.5V6.5m2 12l6-6");
}

.p_wt0acuq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 12.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
