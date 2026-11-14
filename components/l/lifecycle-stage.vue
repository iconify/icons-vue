<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q51ehrbug"/><path class="arph7ccat"/><path class="jiu2_ob8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifecycle-stage" /></template>
<style>
.arph7ccat {
  fill: currentColor;
  d: path("M14.25 2.75a9.5 9.5 0 0 1 7 7l-1.5 1.5l-2-.75a6 6 0 0 0-4.25-4.25Z");
}

.jiu2_ob8a {
  d: path("m14.25 21.25l-1.5-1.5l.75-2m-10.75-3.5l1.5-1.5l2 .75m3.5-10.75l1.5 1.5l-.75 2");
}

.q51ehrbug {
  d: path("M19.52 13.875a7.75 7.75 0 0 1-5.645 5.645m-3.75 0a7.75 7.75 0 0 1-5.645-5.645m0-3.75a7.75 7.75 0 0 1 5.645-5.645");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
