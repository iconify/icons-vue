<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc8pz7gvg"/><path class="mgqdl9arb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-seat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mgqdl9arb {
  d: path("m16.39 3.07l.89 1.99q.15.32.49.36l2.17.23q.35.04.09.27l-1.62 1.46q-.26.24-.19.58l.46 2.14q.07.34-.24.16l-1.89-1.09q-.3-.17-.6 0l-1.89 1.09q-.31.18-.24-.16l.46-2.14q.07-.34-.19-.58l-1.62-1.46q-.26-.23.09-.27l2.17-.23q.34-.04.49-.36l.89-1.99q.14-.32.28 0");
}

.tc8pz7gvg {
  d: path("M5.25 4.25a1.5 1.5 0 0 1 3 0V13h8.5a2 2 0 0 1 2 2v1.5H7.25a2 2 0 0 1-2-2ZM8 16.5v4.75m8.5-4.75v4.75");
}

</style>
