<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hkglpchld"/><path class="bixrf0b_t"/><path class="fgcgcycrv"/><path class="c_pe6njtz"/><path class="bzecsub_a"/><path class="ipr9vreed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-left-to-line-duotone-regular" /></template>
<style>
.bixrf0b_t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bzecsub_a {
  d: path("M8 12h12");
}

.c_pe6njtz {
  d: path("M4 7v10");
}

.fgcgcycrv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hkglpchld {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ipr9vreed {
  d: path("m12 8 -4 4 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
