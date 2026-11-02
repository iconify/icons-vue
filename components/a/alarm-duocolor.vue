<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z3i3f4mzl"/><path class="hzz5rps4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-duocolor" /></template>
<style>
.hzz5rps4c {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 0 0-16 0m8-4v4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z3i3f4mzl {
  stroke-opacity: 0.4;
  d: path("m3 6l3-3m12 0l3 3");
}

</style>
