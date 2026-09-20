<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ar5_4pb4n"/><path class="qasykub6m"/><path class="vp4snv31o"/><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="egsaq3b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-to-line-duotone-bold" /></template>
<style>
.ar5_4pb4n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.egsaq3b2f {
  d: path("m12 8 4 4 -4 4");
}

.jka0cfj-k {
  d: path("M4 12h12");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.qasykub6m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vp4snv31o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
