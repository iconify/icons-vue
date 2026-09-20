<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h0_elcc4n"/><path class="u6y4up8hd"/><path class="xl3k3gb4y"/><path class="fduyhzmeq"/><path class="nt8ufs66i"/><path class="ig8k5lhpw"/><path class="hlt9oudyd"/><path class="goqqd75_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-waterfall-duotone-thin" /></template>
<style>
.fduyhzmeq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.goqqd75_r {
  d: path("M20 4v5");
}

.h0_elcc4n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hlt9oudyd {
  d: path("M15 9v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ig8k5lhpw {
  d: path("M10 11v5");
}

.nt8ufs66i {
  d: path("M5 6v5");
}

.u6y4up8hd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xl3k3gb4y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
