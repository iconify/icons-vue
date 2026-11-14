<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="je9f_bv3o"/><path class="i6l7ot9yu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:goal-alignment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6l7ot9yu {
  d: path("M6.5 14.25v4.5h11v-4.5m-11-4.5h.01m10.99 0h.01m-11.01 0l4.5-4.5m6.5 4.5l4-4");
}

.je9f_bv3o {
  d: path("M2 9.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m11 0a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
