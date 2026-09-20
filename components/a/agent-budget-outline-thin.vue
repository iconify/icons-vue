<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugdbidcqi"/><path class="c4khiwgvb"/><path class="tzv123bil"/><path class="wrji4lgnj"/><path class="h1h08f6go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-budget-outline-thin" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.h1h08f6go {
  d: path("M15 12v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tzv123bil {
  d: path("M9 10v5");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

.wrji4lgnj {
  d: path("M12 8v7");
}

</style>
