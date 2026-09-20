<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="gl3_cfeeg"/><path class="la945tbvd"/><path class="xgrfb-bqu"/><path class="qt4afwy9g"/><path class="ite_ehtoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:align-center-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gl3_cfeeg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6.5 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ite_ehtoh {
  d: path("M4.5 18h15");
}

.la945tbvd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qt4afwy9g {
  d: path("M6.5 12h11");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
