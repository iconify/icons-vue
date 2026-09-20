<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t-xqdgb2z"/><path class="kjfa6tbmq"/><path class="fvteuwbda"/><path class="bgjpknbib"/><path class="tw3a5bcpe"/><path class="lpthwr95f"/><path class="qlfruhq7c"/><path class="zpl29uvhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alignment-duotone-regular" /></template>
<style>
.bgjpknbib {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fvteuwbda {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kjfa6tbmq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h6l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lpthwr95f {
  d: path("M3 17h6l4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlfruhq7c {
  d: path("M13 12h5");
}

.t-xqdgb2z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h6l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tw3a5bcpe {
  d: path("M3 7h6l4 4");
}

.zpl29uvhf {
  d: path("m16 9 3 3 -3 3");
}

</style>
