<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nu0ti3ggl"/><path class="tw9fmib1q"/><path class="xjc8r-b1m"/><path class="qz9_3ub7s"/><path class="vhnbtvbtn"/><path class="pb147jbda"/><path class="wfoy3xxos"/><path class="dznv025mt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hurdles-duotone-bold" /></template>
<style>
.dznv025mt {
  d: path("M6 14h12");
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pb147jbda {
  d: path("M6 8v12");
}

.qz9_3ub7s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tw9fmib1q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.wfoy3xxos {
  d: path("M18 8v12");
}

.xjc8r-b1m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
