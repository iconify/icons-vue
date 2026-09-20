<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o72p0hsyz"/><path class="s97n4nb-h"/><path class="hqoi59sxr"/><path class="z9nuhdbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-understand-outline-regular" /></template>
<style>
.hqoi59sxr {
  d: path("M12 9v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o72p0hsyz {
  d: path("M14 4h4a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h4");
}

.s97n4nb-h {
  d: path("M8 11v5");
}

.z9nuhdbuz {
  d: path("M16 13v3");
}

</style>
