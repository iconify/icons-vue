<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g-qvc03sc"/><path class="q3ca84baq"/><path class="iv9vhg42o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kettle-outline-regular" /></template>
<style>
.g-qvc03sc {
  d: path("M6 10h10v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.iv9vhg42o {
  d: path("M7 10c0 -5 8 -5 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q3ca84baq {
  d: path("m16 11 4 -4");
}

</style>
