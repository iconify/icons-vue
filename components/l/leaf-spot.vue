<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hufyo_fte"/><path class="knutw4vyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-spot" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hufyo_fte {
  d: path("M5 19c0-9 5-14.5 15.5-15.5C19.5 14 14 19 5 19m0 0l-2.5 2.5");
}

.knutw4vyw {
  d: path("M7.25 15.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m7-7a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-2 5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
