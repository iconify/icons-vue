<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="diipsobkl"/><path class="s1m4z10fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cat-flap-outline-regular" /></template>
<style>
.diipsobkl {
  d: path("M5 3v18h14V3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s1m4z10fj {
  d: path("M8 21v-4c0 -2 8 -2 8 0v4");
}

</style>
