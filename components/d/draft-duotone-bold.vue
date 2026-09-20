<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lmauonb1j"/><path class="faaxtxspp"/><path class="wdpkdo6us"/><path class="w0as59itk"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:draft-duotone-bold" /></template>
<style>
.aum97lbyp {
  d: path("M9 13h4");
}

.faaxtxspp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.lmauonb1j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 3H6v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w0as59itk {
  d: path("M13 3H6v18h8");
}

.wdpkdo6us {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
