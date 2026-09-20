<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="qfxaj1b6z"/><path class="sbrnxdfkc"/><path class="xbphpkb7w"/><path class="r3faxubne"/><path class="rxxtm7qkj"/><path class="einbtqqgb"/><path class="mldnorr-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-duotone-regular" /></template>
<style>
.einbtqqgb {
  d: path("M7 12h13");
}

.mldnorr-p {
  d: path("M7 17h13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pd-i35blz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qfxaj1b6z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.rxxtm7qkj {
  d: path("M7 7h13");
}

.sbrnxdfkc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xbphpkb7w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
