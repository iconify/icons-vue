<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="giopbjb9g"/><path class="h_alycbda"/><path class="lb5uptbbe"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grass-outline-thin" /></template>
<style>
.giopbjb9g {
  d: path("M5 19v-7l3 -3");
}

.h_alycbda {
  d: path("M10 19v-9l3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lb5uptbbe {
  d: path("M16 19v-7l3 -3");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

</style>
