<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="of4kfwcob"/><path class="n1-_lub_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:feedback-loop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1-_lub_g {
  d: path("m12.14 7.07l.89 1.99q.15.32.49.36l2.17.23q.35.04.09.27l-1.62 1.46q-.26.24-.19.58l.46 2.14q.07.34-.24.16l-1.89-1.09q-.3-.17-.6 0l-1.89 1.09q-.31.18-.24-.16l.46-2.14q.07-.34-.19-.58L8.22 9.92q-.26-.23.09-.27l2.17-.23q.34-.04.49-.36l.89-1.99q.14-.32.28 0");
}

.of4kfwcob {
  d: path("M2.75 6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v9a2.5 2.5 0 0 1-2.5 2.5H12.5L8 20.85a.77.77 0 0 1-1.25-.6v-2.5h-1.5a2.5 2.5 0 0 1-2.5-2.5Z");
}

</style>
