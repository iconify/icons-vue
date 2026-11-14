<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6mx6p8ck"/><path class="cpjucyb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:detour-route" /></template>
<style>
.cpjucyb5e {
  d: path("M18.75 12.25L21.5 15l-2.75 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6mx6p8ck {
  d: path("M2.5 15H6c2 0 2-9 6-9s4 9 6 9h3.5");
}

</style>
