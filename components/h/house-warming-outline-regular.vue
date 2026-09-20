<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsz3y4a_c"/><path class="u-niy3p1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-warming-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsz3y4a_c {
  d: path("M4 19v-7l7 -7 7 7v7Z");
}

.u-niy3p1t {
  d: path("M11 16c-2 -1 -2 -4 0 -5 2 1 2 4 0 5");
}

</style>
