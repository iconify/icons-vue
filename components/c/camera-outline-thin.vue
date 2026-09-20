<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o5fggbv0a"/><path class="jkhzseaxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:camera-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkhzseaxg {
  d: path("M8.5 13.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.o5fggbv0a {
  d: path("M14 7h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-7a3 3 0 0 1 3 -3h5");
}

</style>
