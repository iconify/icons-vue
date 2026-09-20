<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d8rc3nxyd"/><path class="n3xdkacev"/><path class="mwzbzwqqg"/><path class="qvqi41cih"/><path class="j2aic6ujd"/><path class="c3xkdj8uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-escalate-duotone-bold" /></template>
<style>
.c3xkdj8uw {
  d: path("M14.5 5H19v4.5");
}

.d8rc3nxyd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2aic6ujd {
  d: path("m12 12 7 -7");
}

.mwzbzwqqg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 5H19v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n3xdkacev {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 12 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qvqi41cih {
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
