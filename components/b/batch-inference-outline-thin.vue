<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l__d61o9z"/><path class="ulrt12bon"/><path class="h4br4z40f"/><path class="tus1_ob4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:batch-inference-outline-thin" /></template>
<style>
.h4br4z40f {
  d: path("M2 12h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l__d61o9z {
  d: path("M16.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3h-8a3 3 0 0 1 -3 -3V7l3 -3h2.5");
}

.tus1_ob4y {
  d: path("M2 16h4");
}

.ulrt12bon {
  d: path("M2 8h4");
}

</style>
