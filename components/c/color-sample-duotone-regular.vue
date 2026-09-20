<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdh3cdbsp"/><path class="jz0b4rbqp"/><path class="tu9hygbmi"/><path class="hecisrt9f"/><path class="fg8libqda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:color-sample-duotone-regular" /></template>
<style>
.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hecisrt9f {
  d: path("m9 14 4 -4 3 3 -4 4Z");
}

.jz0b4rbqp {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.qdh3cdbsp {
  fill: currentColor;
  d: path("m9 14 4 -4 3 3 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tu9hygbmi {
  d: path("m13 4 6 6");
}

</style>
