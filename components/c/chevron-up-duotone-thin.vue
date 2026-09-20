<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f04gvrxqu"/><path class="sbpsi82ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-up-duotone-thin" /></template>
<style>
.f04gvrxqu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 15 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbpsi82ym {
  d: path("m5 15 7 -7 7 7");
}

</style>
