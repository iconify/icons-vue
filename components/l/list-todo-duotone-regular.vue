<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ltk4lt95w"/><path class="b9hsu5b7d"/><path class="uvibyebdw"/><path class="b5p141rkx"/><path class="yt7lrkbdr"/><path class="loif6ccvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-todo-duotone-regular" /></template>
<style>
.b5p141rkx {
  d: path("M11 7.5h10");
}

.b9hsu5b7d {
  fill: currentColor;
  d: path("M3 14h5v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.loif6ccvl {
  d: path("M11 16.5h10");
}

.ltk4lt95w {
  fill: currentColor;
  d: path("M3 5h5v5H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uvibyebdw {
  d: path("M3 5h5v5H3Z");
}

.yt7lrkbdr {
  d: path("M3 14h5v5H3Z");
}

</style>
