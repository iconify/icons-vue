<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="q_x3fkbpj"/><path class="t08wuz0fb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lug-nut" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.q_x3fkbpj {
  d: path("m17.065 12.752l-1.882 3.25a1.5 1.5 0 0 1-1.298.748h-3.77a1.5 1.5 0 0 1-1.298-.748l-1.882-3.25a1.5 1.5 0 0 1 0-1.504l1.882-3.25a1.5 1.5 0 0 1 1.298-.748h3.77a1.5 1.5 0 0 1 1.298.748l1.882 3.25a1.5 1.5 0 0 1 0 1.504");
}

.t08wuz0fb {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
