<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aqrf9ebcv"/><path class="bo9im64yu"/><path class="qr53q-zec"/><path class="phjgeccqs"/><path class="vhnbtvbtn"/><path class="pb147jbda"/><path class="wfoy3xxos"/><path class="dznv025mt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hurdles-duotone-regular" /></template>
<style>
.aqrf9ebcv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bo9im64yu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dznv025mt {
  d: path("M6 14h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pb147jbda {
  d: path("M6 8v12");
}

.phjgeccqs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qr53q-zec {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.wfoy3xxos {
  d: path("M18 8v12");
}

</style>
