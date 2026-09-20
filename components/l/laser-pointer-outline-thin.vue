<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r_2fvubda"/><path class="qh7t7707e"/><path class="p2apttb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laser-pointer-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2apttb3i {
  d: path("M17.5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qh7t7707e {
  d: path("m9 16.5 7 -7");
}

.r_2fvubda {
  d: path("M2 19a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

</style>
