<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xcmjvmbet"/><path class="y8vn3_qip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exit-door-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcmjvmbet {
  d: path("M14 7.5v-5H4v19h10v-5");
}

.y8vn3_qip {
  d: path("m6.077 3.365l3 1.25A1.5 1.5 0 0 1 10 6v12a1.5 1.5 0 0 1-.923 1.385l-3 1.25A1.5 1.5 0 0 1 4 19.25V4.75a1.5 1.5 0 0 1 2.077-1.385M13 12h8m-3.5-3.5L21 12l-3.5 3.5");
}

</style>
