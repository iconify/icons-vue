<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="qt-ju5b4m"/><path class="m-_z-lb4c"/><path class="gvkfsgbpl"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f-mjnibpi"/><path class="w6105m-jv"/><path class="nwor_i7ms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-horizontal-duotone-regular" /></template>
<style>
.f-mjnibpi {
  d: path("M4 7h12");
}

.gvkfsgbpl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-_z-lb4c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwor_i7ms {
  d: path("M4 17h14");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qt-ju5b4m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.w6105m-jv {
  d: path("M4 12h8");
}

</style>
