<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vx9rskbcr"/><path class="ryj_7f_2r"/><path class="o-ypo56nb"/><path class="vlkt4vbcy"/><path class="xf07dvr8m"/><path class="ml3aqbbkk"/><path class="rw2cw9fuy"/><path class="pq2hynbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bandwidth-cap-duotone-bold" /></template>
<style>
.ml3aqbbkk {
  d: path("M4 8v12");
}

.o-ypo56nb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq2hynbuc {
  d: path("m6 18 4 -4 3 3 6 -6");
}

.rw2cw9fuy {
  d: path("M4 20h17");
}

.ryj_7f_2r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vlkt4vbcy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 18 4 -4 3 3 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vx9rskbcr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xf07dvr8m {
  d: path("M2 5h20");
}

</style>
