<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nln8svb8x"/><path class="x005182si"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:colosseum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nln8svb8x {
  d: path("M2.75 20.25V7.75q0-.9.85-1.2Q9 4.5 14.25 4.75a.75.75 0 0 1 .75.75v2.25a.75.75 0 0 0 .75.75h2a.75.75 0 0 1 .75.75v2.25a.75.75 0 0 0 .75.75h1a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1m0-5.75h18.5");
}

.x005182si {
  d: path("M5.75 11.5v-1.25a1.5 1.5 0 0 1 3 0v1.25Zm6 0v-1.25a1.5 1.5 0 0 1 3 0v1.25Zm-6 9.75V19.5a2 2 0 0 1 4 0v1.75m4.5 0V19.5a2 2 0 0 1 4 0v1.75");
}

</style>
