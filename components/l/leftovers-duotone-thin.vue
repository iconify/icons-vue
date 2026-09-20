<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vsuxsbsia"/><path class="ydwr2p6jl"/><path class="x50q_4bdr"/><path class="mhnr27bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leftovers-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhnr27bap {
  d: path("M12 7v3");
}

.vsuxsbsia {
  fill: currentColor;
  d: path("M5 13v7h14v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.ydwr2p6jl {
  d: path("M5 13v7h14v-7Z");
}

</style>
