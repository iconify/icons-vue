<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhfhm4bia"/><path class="bv708k7dd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chocolate-shop" /></template>
<style>
.bv708k7dd {
  d: path("M3 9a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0M6.5 20.5v-5h4v5m6.25-5.25h3A1.75 1.75 0 0 1 21.5 17v3.25A1.75 1.75 0 0 1 19.75 22h-3A1.75 1.75 0 0 1 15 20.25V17a1.75 1.75 0 0 1 1.75-1.75m1.5 0V22M15 18.5h6.5");
}

.fhfhm4bia {
  d: path("m3 9l1.5-5h15L21 9m-1.5 2v1.4M4.5 11v9.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
