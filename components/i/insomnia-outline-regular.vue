<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v105zmblb"/><path class="r3k61hkwm"/><path class="t06rkwfxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:insomnia-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r3k61hkwm {
  d: path("M20 5v7");
}

.t06rkwfxk {
  d: path("M19 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.v105zmblb {
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
}

</style>
