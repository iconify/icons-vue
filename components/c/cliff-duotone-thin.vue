<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6zbhsh2k"/><path class="n2-eu36vv"/><path class="ior14cbcm"/><path class="hr8ceclju"/><path class="rn2_dtbur"/><path class="ubbszwy6j"/><path class="z9ittvbis"/><path class="a562fv74t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cliff-duotone-thin" /></template>
<style>
.a562fv74t {
  d: path("M6 22h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr8ceclju {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 22h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n2-eu36vv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 8 4 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6zbhsh2k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3h10v13H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rn2_dtbur {
  d: path("M3 3h10v13H3");
}

.ubbszwy6j {
  d: path("m13 8 4 4v4");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
