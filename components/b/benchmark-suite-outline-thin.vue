<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="c0p3a4scc"/><path class="hqoi59sxr"/><path class="lhg9en3sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:benchmark-suite-outline-thin" /></template>
<style>
.c0p3a4scc {
  d: path("M9 11v5");
}

.dx3ubrb9h {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.hbtmd5b0k {
  d: path("M9.5 7V2.5h5V7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqoi59sxr {
  d: path("M12 9v7");
}

.lhg9en3sp {
  d: path("M15 13v3");
}

</style>
