<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b8ajlyx7w"/><path class="oigar205c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eject-duocolor-round" /></template>
<style>
.b8ajlyx7w {
  stroke-opacity: 0.4;
  d: path("M5 20h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oigar205c {
  d: path("m5.504 11.336l4-6c1.187-1.781 3.805-1.781 4.992 0l4 6C19.826 13.33 18.396 16 16 16H8c-2.396 0-3.825-2.67-2.496-4.664");
}

</style>
