<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbllh8b8w"/><path class="o3r8utdvv"/><path class="no2cffbmc"/><path class="u5fslkbip"/><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-drop-duotone-regular" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.lbllh8b8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.o3r8utdvv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.u5fslkbip {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

.yhbiuccel {
  d: path("m16 16 3 3 3 -3");
}

</style>
