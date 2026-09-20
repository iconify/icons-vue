<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="xgrnk0bjr"/><path class="fdrffh_te"/><path class="afe35-b1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:folder-tree-duotone-bold" /></template>
<style>
.afe35-b1h {
  d: path("M9 17h5");
}

.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.fdrffh_te {
  d: path("M9 13h5");
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgrnk0bjr {
  d: path("M9 10v7");
}

</style>
