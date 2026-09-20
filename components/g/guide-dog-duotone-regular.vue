<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oa25tib0b"/><path class="vvz7c8b5l"/><path class="c1k0xv-8t"/><path class="r61xwob3k"/><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guide-dog-duotone-regular" /></template>
<style>
.avtblzbgk {
  d: path("M6 20v-7h10v7");
}

.c1k0xv-8t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 7 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.krhtkbcno {
  d: path("m6 13 -3 -3");
}

.midjlmbqm {
  d: path("m16 7 -3 -3");
}

.nie_edcrf {
  d: path("M16 13V7h5v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oa25tib0b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20v-7h10v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r61xwob3k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 13 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vvz7c8b5l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 13V7h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
