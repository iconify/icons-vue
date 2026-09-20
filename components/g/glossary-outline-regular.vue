<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="u9fo-tizz"/><path class="uxyzhxvwz"/><path class="dkyw6nb7m"/><path class="kzhxz3b3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:glossary-outline-regular" /></template>
<style>
.dkyw6nb7m {
  d: path("M7 16h7");
}

.kzhxz3b3w {
  d: path("M13 8h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u9fo-tizz {
  d: path("M7 8h4");
}

.uxyzhxvwz {
  d: path("M7 12h10");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
