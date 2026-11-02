<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izd9lacbg"/><path class="fs89iqu4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-help-duocolor-sharp" /></template>
<style>
.fs89iqu4z {
  d: path("m17 17l-5 5L2 12L12 2l10 10z");
}

.izd9lacbg {
  stroke-opacity: 0.4;
  d: path("M10 11a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
