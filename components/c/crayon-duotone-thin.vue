<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tv_tj5b9h"/><path class="o47um4vmm"/><path class="j5baogbem"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crayon-duotone-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5baogbem {
  d: path("M8 11h8");
}

.o47um4vmm {
  d: path("M8 21V9l4 -4 4 4v12Z");
}

.tv_tj5b9h {
  fill: currentColor;
  d: path("M8 21V9l4 -4 4 4v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
