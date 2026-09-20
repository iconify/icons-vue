<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h033mmb1s"/><path class="vdjnqqbyj"/><path class="dlslqyb1j"/><path class="ssnrvvbod"/><path class="c7dgfu7wx"/><path class="n-z4jv76k"/><path class="qagp93bmg"/><path class="diaqyhfcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:darkroom-duotone-regular" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.diaqyhfcp {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dlslqyb1j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4v14h10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h033mmb1s {
  fill: currentColor;
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-z4jv76k {
  d: path("M7 4v14h10V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qagp93bmg {
  d: path("m9 14 3 -3 3 3");
}

.ssnrvvbod {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 14 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdjnqqbyj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
