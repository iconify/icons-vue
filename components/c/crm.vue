<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vbz9c3m2c"/><path class="ogbtfdbcm"/><path class="vnrefqbky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ogbtfdbcm {
  d: path("M5.5 10V8.5A1.5 1.5 0 0 1 7 7h10a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 17 17h-1.5");
}

.vbz9c3m2c {
  d: path("M5.125 10h7.75a2.625 2.625 0 0 1 2.625 2.625v4.75A2.625 2.625 0 0 1 12.875 20h-7.75A2.625 2.625 0 0 1 2.5 17.375v-4.75A2.625 2.625 0 0 1 5.125 10");
}

.vnrefqbky {
  d: path("M8.5 7V5.5A1.5 1.5 0 0 1 10 4h10a1.5 1.5 0 0 1 1.5 1.5v7A1.5 1.5 0 0 1 20 14h-1.5m-13 1h5");
}

</style>
