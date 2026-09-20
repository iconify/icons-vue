<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hwufvfb8q"/><path class="di1jgfeil"/><path class="tcb1h8bbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:family-house-outline-regular" /></template>
<style>
.di1jgfeil {
  d: path("M16 8V4h3v7");
}

.hwufvfb8q {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tcb1h8bbm {
  d: path("M9 20v-6h6v6");
}

</style>
