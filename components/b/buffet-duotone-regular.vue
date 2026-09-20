<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w5o7xublt"/><path class="jcq7_3bye"/><path class="pdk95vb_h"/><path class="ewow7lb8i"/><path class="tl-k-tuga"/><path class="zugrvnb7t"/><path class="e325robmt"/><path class="bfcwd7bcm"/><path class="v7ifz5bvw"/><path class="leijmjbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:buffet-duotone-regular" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.ewow7lb8i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jcq7_3bye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.leijmjbkg {
  d: path("M18 13v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdk95vb_h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tl-k-tuga {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7ifz5bvw {
  d: path("M6 13v6");
}

.w5o7xublt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
