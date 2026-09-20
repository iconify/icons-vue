<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg_qr_bas"/><path class="zi4feub_h"/><path class="d7smd9b8i"/><path class="v5_ol6yqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breeze-duotone-thin" /></template>
<style>
.d7smd9b8i {
  d: path("M2 8h13a3.5 3.5 0 1 0 -3.5 -3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg_qr_bas {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h13a3.5 3.5 0 1 0 -3.5 -3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v5_ol6yqz {
  d: path("M2 17h12a3.5 3.5 0 1 0 -3.5 3.5");
}

.zi4feub_h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 17h12a3.5 3.5 0 1 0 -3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
