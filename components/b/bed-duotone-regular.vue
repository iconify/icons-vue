<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq6pgiv_p"/><path class="zkem-xbdf"/><path class="vtu55j5ep"/><path class="azx0_b4zo"/><path class="jerybmbxk"/><path class="et-iwmblh"/><path class="nqnw98byf"/><path class="f0qz9mbvk"/><path class="t3iybibvf"/><path class="wbz8a-gmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bed-duotone-regular" /></template>
<style>
.azx0_b4zo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.et-iwmblh {
  d: path("M2 18v-7h20v7");
}

.f0qz9mbvk {
  d: path("M4 11V7h6v4");
}

.jerybmbxk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nqnw98byf {
  d: path("M2 14h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pq6pgiv_p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t3iybibvf {
  d: path("M3 18v2.5");
}

.vtu55j5ep {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11V7h6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wbz8a-gmi {
  d: path("M21 18v2.5");
}

.zkem-xbdf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
