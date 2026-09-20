<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8hz-1b0o"/><path class="d7v1u0n6f"/><path class="c_wz_w0ix"/><path class="rpp4spbxo"/><path class="nh1hchbhr"/><path class="tp19rhqzz"/><path class="gcbumkb_o"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:altitude-duotone-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.c_wz_w0ix {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 5.5 19 3l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d7v1u0n6f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gcbumkb_o {
  d: path("M16.5 5.5 19 3l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8hz-1b0o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 18 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nh1hchbhr {
  d: path("m3 18 7 -7 7 7");
}

.rpp4spbxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tp19rhqzz {
  d: path("M19 3v15");
}

</style>
