<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ydwr2p6jl"/><path class="x50q_4bdr"/><path class="mhnr27bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leftovers-outline-regular" /></template>
<style>
.mhnr27bap {
  d: path("M12 7v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.ydwr2p6jl {
  d: path("M5 13v7h14v-7Z");
}

</style>
