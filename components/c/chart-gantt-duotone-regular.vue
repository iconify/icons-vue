<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="bsgefc34w"/><path class="aeb4_busl"/><path class="fgp9a0qmd"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r_r678bum"/><path class="lqiw_3bos"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gantt-duotone-regular" /></template>
<style>
.aeb4_busl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bsgefc34w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fgp9a0qmd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r_r678bum {
  d: path("M6 7h6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

</style>
