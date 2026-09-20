<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vch9hc4be"/><path class="fydnuyb9t"/><path class="pfvjrtb4r"/><path class="ji4qr0fvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clone-outline-thin" /></template>
<style>
.fydnuyb9t {
  d: path("M13 15a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji4qr0fvp {
  d: path("M15 8h3V5");
}

.pfvjrtb4r {
  d: path("m15 5 3 3");
}

.vch9hc4be {
  d: path("M2 4a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
