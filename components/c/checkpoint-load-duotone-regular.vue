<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vn749yfck"/><path class="qkrt1qbaa"/><path class="no2cffbmc"/><path class="iqekvccuu"/><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="hpd-e505b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-load-duotone-regular" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.hpd-e505b {
  d: path("M16.5 15.5 19 13l2.5 2.5");
}

.iqekvccuu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 15.5 19 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ni-_lk7vs {
  d: path("M5 5h10v6H5");
}

.no2cffbmc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ojq3d2bwe {
  d: path("M5 3v18");
}

.qkrt1qbaa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 5h10v6H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vn749yfck {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
