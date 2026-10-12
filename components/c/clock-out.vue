<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dldnhmbjp"/><path class="c4u03w6hx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clock-out" /></template>
<style>
.c4u03w6hx {
  d: path("M12 7.25V12l-3 2m6 1l5.5 5.5m0-3.75v3.75h-3.75");
}

.dldnhmbjp {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
