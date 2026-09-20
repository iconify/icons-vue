<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umdodccwv"/><path class="ovzzbs_1x"/><path class="zhzzk2fcp"/><path class="cllzgnvrr"/><path class="orxbg_b1j"/><path class="zuuudpbwi"/><path class="rdidnh2az"/><path class="isrkj8blm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dedupe-fuzzy-duotone-thin" /></template>
<style>
.cllzgnvrr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isrkj8blm {
  d: path("M3 17h13");
}

.orxbg_b1j {
  d: path("M3 4h13");
}

.ovzzbs_1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rdidnh2az {
  d: path("m10 11.5 2 2 2 -2");
}

.umdodccwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zhzzk2fcp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuuudpbwi {
  d: path("M3 8h14");
}

</style>
