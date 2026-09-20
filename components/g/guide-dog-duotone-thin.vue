<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zi2vgzezl"/><path class="lfyxabcmu"/><path class="w9vap4dng"/><path class="bv0s6abdo"/><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guide-dog-duotone-thin" /></template>
<style>
.avtblzbgk {
  d: path("M6 20v-7h10v7");
}

.bv0s6abdo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 13 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.krhtkbcno {
  d: path("m6 13 -3 -3");
}

.lfyxabcmu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 13V7h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.midjlmbqm {
  d: path("m16 7 -3 -3");
}

.nie_edcrf {
  d: path("M16 13V7h5v4");
}

.w9vap4dng {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 7 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zi2vgzezl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20v-7h10v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
