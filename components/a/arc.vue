<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j7crcziyc"/><path class="qs-y-_biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arc" /></template>
<style>
.j7crcziyc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5a8.5 8.5 0 0 1 17 0m-17.75 0h1.5m15.5 0h1.5");
}

.qs-y-_biw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
