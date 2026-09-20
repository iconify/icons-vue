<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nlx-15cix"/><path class="eylqpv51p"/><path class="a6m5kfb7k"/><path class="e7q8l6x6g"/><path class="osdsz4bam"/><path class="iup9trbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-bisect-outline-regular" /></template>
<style>
.a6m5kfb7k {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e7q8l6x6g {
  d: path("M6 14h5");
}

.eylqpv51p {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iup9trbmr {
  d: path("M12 6v4");
}

.nlx-15cix {
  d: path("M4 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osdsz4bam {
  d: path("M13 14h5");
}

</style>
