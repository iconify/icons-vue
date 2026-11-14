<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbxjcfbvt"/><path class="mvuvx5bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gerbera" /></template>
<style>
.hbxjcfbvt {
  d: path("m12.625 3.625l.015.038a1.305 1.305 0 0 0 1.985.587a.651.651 0 0 1 1.019.662l-.027.127A1.415 1.415 0 0 0 17 6.75a.625.625 0 0 1 .396 1.108l-.021.017a1.454 1.454 0 0 0 0 2.25l.021.017A.625.625 0 0 1 17 11.25a1.415 1.415 0 0 0-1.383 1.711l.027.127a.651.651 0 0 1-1.019.662a1.305 1.305 0 0 0-1.985.587l-.015.038a.67.67 0 0 1-1.25 0l-.015-.038a1.305 1.305 0 0 0-1.985-.587a.651.651 0 0 1-1.019-.662l.027-.127A1.415 1.415 0 0 0 7 11.25a.625.625 0 0 1-.396-1.108l.021-.017a1.454 1.454 0 0 0 0-2.25l-.021-.017A.625.625 0 0 1 7 6.75a1.415 1.415 0 0 0 1.383-1.711l-.027-.127a.651.651 0 0 1 1.019-.662a1.305 1.305 0 0 0 1.985-.587l.015-.038a.67.67 0 0 1 1.25 0M12 16v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mvuvx5bdi {
  d: path("M10.75 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
