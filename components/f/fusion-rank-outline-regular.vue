<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mjze8rg7o"/><path class="olzrbkb7x"/><path class="mo-ktlbjm"/><path class="te5l3v53b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fusion-rank-outline-regular" /></template>
<style>
.mjze8rg7o {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

.mo-ktlbjm {
  d: path("M10.5 18h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olzrbkb7x {
  d: path("M9 15.5v5");
}

.te5l3v53b {
  d: path("M15 15.5v5");
}

</style>
