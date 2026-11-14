<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q-76wqpon"/><path class="ntnrf5tzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-power-kw" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntnrf5tzs {
  d: path("m10.046 8.223l-1.451 2.678A.745.745 0 0 0 9.25 12a.998.998 0 0 1 .973 1.219l-.348 1.531a.426.426 0 0 0 .784.307l1.716-2.974A.722.722 0 0 0 11.75 11a1.076 1.076 0 0 1-1.065-1.236l.19-1.264a.444.444 0 0 0-.829-.277");
}

.q-76wqpon {
  d: path("M4 21.5v-17a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v17m-13.5 0h15M16 8h1.5a2 2 0 0 1 2 2v5");
}

</style>
