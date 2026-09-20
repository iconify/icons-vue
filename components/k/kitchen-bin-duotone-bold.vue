<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ygf5spb0x"/><path class="nu0ti3ggl"/><path class="biinxi2ez"/><path class="veh2lgbsg"/><path class="odlchqg5v"/><path class="vhnbtvbtn"/><path class="h2-rujbru"/><path class="azrfjy1oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kitchen-bin-duotone-bold" /></template>
<style>
.azrfjy1oo {
  d: path("M14 5v3");
}

.biinxi2ez {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-rujbru {
  d: path("M10 5v3");
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.odlchqg5v {
  d: path("M6 9c0.5 4 1 8 2 11h8c1 -3 1.5 -7 2 -11");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.veh2lgbsg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.ygf5spb0x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9c0.5 4 1 8 2 11h8c1 -3 1.5 -7 2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
