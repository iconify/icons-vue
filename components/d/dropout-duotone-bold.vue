<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="eb8o-4buj"/><path class="yp_l0abrr"/><path class="h2sq3fbpa"/><path class="xgrfb-bqu"/><path class="d223d_x9q"/><path class="nuz6-76is"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dropout-duotone-bold" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.eb8o-4buj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2sq3fbpa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.khksl7boy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nuz6-76is {
  d: path("M15 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.yp_l0abrr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
