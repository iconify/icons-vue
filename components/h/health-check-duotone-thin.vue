<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vgel1-xvj"/><path class="i7kaf-qlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-check-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7kaf-qlz {
  d: path("M3 12h5V6h4v12h4v-6h5");
}

.vgel1-xvj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h5V6h4v12h4v-6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
