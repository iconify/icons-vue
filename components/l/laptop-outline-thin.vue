<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="othqh9bcz"/><path class="z9ittvbis"/><path class="s9zlrxyyc"/><path class="ejc7sbawl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laptop-outline-thin" /></template>
<style>
.ejc7sbawl {
  d: path("M20 15v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.othqh9bcz {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.s9zlrxyyc {
  d: path("M4 15v4");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
