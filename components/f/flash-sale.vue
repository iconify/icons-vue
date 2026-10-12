<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9k8jk4mn"/><path class="uw3jnusza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flash-sale" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9k8jk4mn {
  d: path("M5.1 8.4a1.75 1.75 0 0 1 1.74-1.65h10.32A1.75 1.75 0 0 1 18.9 8.4l.7 10.3a2.5 2.5 0 0 1-2.5 2.55H6.9a2.5 2.5 0 0 1-2.5-2.55Z");
}

.uw3jnusza {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25m-2.5 1l-2.5 4h3.5l-2.5 4");
}

</style>
