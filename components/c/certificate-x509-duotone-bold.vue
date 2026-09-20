<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uhkv12boy"/><path class="gjg57ibhd"/><path class="lyyswacbl"/><path class="uxsptjbvt"/><path class="m1b4e0b4z"/><path class="kc5-9ib3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:certificate-x509-duotone-bold" /></template>
<style>
.gjg57ibhd {
  fill: currentColor;
  d: path("M9 18.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kc5-9ib3u {
  d: path("M9 18.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.lyyswacbl {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.m1b4e0b4z {
  d: path("M6 11h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uhkv12boy {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uxsptjbvt {
  d: path("M6 7h12");
}

</style>
