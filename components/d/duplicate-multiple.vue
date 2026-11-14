<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vgsxopb1j"/><path class="pbqudibor"/><path class="dv344qf1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duplicate-multiple" /></template>
<style>
.dv344qf1f {
  d: path("M3.5 13.5v-8a2 2 0 0 1 2-2h8");
}

.pbqudibor {
  d: path("M6.75 17V8.75a2 2 0 0 1 2-2H17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vgsxopb1j {
  d: path("M10 10h10.5v10.5H10Z");
}

</style>
