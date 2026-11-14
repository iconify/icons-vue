<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7j4vuisp"/><path class="aa-12mb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dragon-head" /></template>
<style>
.aa-12mb3n {
  d: path("M9 9C7.5 7.5 5.5 7 3 7m14.5 5l.75 2l.75-2m-5-2h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7j4vuisp {
  d: path("M5 21.5C5 16 6 12 9 9l1.5-2.5l3.5 1L21 9v3h-6l5 3.5v2h-6c-2 .5-3 2-3 4m-.5-15C9 4.5 6.5 3 3 2.5");
}

</style>
