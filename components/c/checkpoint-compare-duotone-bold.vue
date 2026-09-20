<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="grqrtqbcz"/><path class="uas13xllp"/><path class="li6wqfgrn"/><path class="crv4i00bu"/><path class="y-rdj5vjt"/><path class="tmdcbizpt"/><path class="l3l5pbb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-compare-duotone-bold" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.grqrtqbcz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h6.5v5H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l3l5pbb3j {
  d: path("M14 9h6.5v5H14");
}

.li6wqfgrn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 9h6.5v5H14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tmdcbizpt {
  d: path("M14 3v18");
}

.uas13xllp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y-rdj5vjt {
  d: path("M4 5h6.5v5H4");
}

</style>
