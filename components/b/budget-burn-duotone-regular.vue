<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="rbrtppjye"/><path class="lvl7hpb5p"/><path class="hbpjze26r"/><path class="adb205iso"/><path class="xgrfb-bqu"/><path class="w8fmvxwit"/><path class="u_m1dmgxz"/><path class="m2_htfbkw"/><path class="vwjblmbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-burn-duotone-regular" /></template>
<style>
.adb205iso {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 17v3h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hbpjze26r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 16 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lvl7hpb5p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m2_htfbkw {
  d: path("m17 16 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rbrtppjye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u_m1dmgxz {
  d: path("M3 16h10");
}

.vwjblmbrl {
  d: path("M21 17v3h-3");
}

.w8fmvxwit {
  d: path("M3 11h14");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
