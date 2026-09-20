<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ob3bf9b2i"/><path class="r4bxr4bnm"/><path class="ljz_vjbfq"/><path class="phj3jm8ef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:label-queue-outline-regular" /></template>
<style>
.ljz_vjbfq {
  d: path("M7 6.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ob3bf9b2i {
  d: path("M5 3h10l3.5 3.5L15 10H5Z");
}

.phj3jm8ef {
  d: path("M7 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.r4bxr4bnm {
  d: path("M5 14h10l3.5 3.5L15 21H5Z");
}

</style>
