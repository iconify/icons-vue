<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6035zrya"/><path class="mnksyngyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dormer" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6035zrya {
  d: path("m2.75 19.25l18.5-5M7 17.4v-7.3q0-.6.42-1.02l4.16-4.16q.42-.42.84 0l4.16 4.16q.42.42.42 1.02v4.7q0 .6-.58.75l-8.84 2.3Q7 18 7 17.4");
}

.mnksyngyk {
  d: path("M10.5 10.5h3a.5.5 0 0 1 .5.5v1.5a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V11a.5.5 0 0 1 .5-.5");
}

</style>
