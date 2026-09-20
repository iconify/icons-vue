<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cqa5wmi5c"/><path class="mf1x1ebvc"/><path class="mwec8jblq"/><path class="tp3wfdbxm"/><path class="tqteed1fm"/><path class="hqkel0bnd"/><path class="uaurn5bqf"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canyon-duotone-bold" /></template>
<style>
.cqa5wmi5c {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 3h6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hqkel0bnd {
  d: path("M22 3h-6v18");
}

.mf1x1ebvc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 3h-6v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mwec8jblq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tp3wfdbxm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tqteed1fm {
  d: path("M2 3h6v18");
}

.uaurn5bqf {
  d: path("m8 17 2 -2 2 2 2 -2 2 2");
}

</style>
