<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l0kls7hkm"/><path class="vgmpjzj8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biomethane-injection" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0kls7hkm {
  d: path("M11 19.75v-7a1.75 1.75 0 0 1 .543-1.267l3.5-3.334a1.75 1.75 0 0 1 2.414 0l3.5 3.334a1.75 1.75 0 0 1 .543 1.267v7a1.75 1.75 0 0 1-1.75 1.75h-7A1.75 1.75 0 0 1 11 19.75M2.5 14H11m-8.5 3H11M6 2.5C8.5 5 9 6.5 9 8a3 3 0 0 1-6 0c0-1.25.75-2.25 1.75-3C5 6 5.5 6.5 6 6.75C6 5.25 5.5 4 6 2.5");
}

.vgmpjzj8o {
  d: path("m13.75 13l2.5 2.5l-2.5 2.5");
}

</style>
