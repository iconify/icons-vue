<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/><path class="jlsc9oajw"/><path class="h3yzlbw2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-outline-regular" /></template>
<style>
.fsv7g_bbj {
  d: path("M9 21H3v-6");
}

.h3yzlbw2w {
  d: path("M14 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.jlsc9oajw {
  d: path("M6 10a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.l6e2wzbuh {
  d: path("M3 9V3h6");
}

.ne_b8wtyo {
  d: path("M21 15v6h-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qtj-xccdg {
  d: path("M15 3h6v6");
}

</style>
