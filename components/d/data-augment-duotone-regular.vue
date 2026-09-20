<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="dx4yo_bup"/><path class="dd2oi04rr"/><path class="bww646bld"/><path class="j_cm6er4j"/><path class="ha74cs_zj"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-augment-duotone-regular" /></template>
<style>
.bww646bld {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dx4yo_bup {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ha74cs_zj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_cm6er4j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j835zw5-z {
  d: path("M3 9h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.ndv19xfog {
  d: path("M3 14h10");
}

.nlg6c6b-z {
  d: path("M18.5 12v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qypknac_m {
  d: path("M16.5 14h4");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s1ajs51ib {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
