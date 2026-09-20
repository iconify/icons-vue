<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jw0risdcq"/><path class="j6xe62btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chunk-overlap-outline-regular" /></template>
<style>
.j6xe62btt {
  d: path("M8 15.5a2.5 2.5 0 0 1 2.5 -2.5h8a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 8 15.5");
}

.jw0risdcq {
  d: path("M3 7.5A2.5 2.5 0 0 1 5.5 5h8A2.5 2.5 0 0 1 16 7.5a2.5 2.5 0 0 1 -2.5 2.5h-8A2.5 2.5 0 0 1 3 7.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
