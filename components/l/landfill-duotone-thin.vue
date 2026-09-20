<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5t0udutl"/><path class="rpp4spbxo"/><path class="k78-gssaa"/><path class="gpip01bqy"/><path class="bod4n0b3z"/><path class="e-n_8dpfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landfill-duotone-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.e-n_8dpfy {
  d: path("m9 13 2 -2");
}

.gpip01bqy {
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k78-gssaa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 13 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rpp4spbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w5t0udutl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
