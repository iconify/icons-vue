<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="oq71y_3bz"/><path class="xaz90clio"/><path class="ftolpwp2e"/><path class="fnu2_gbjz"/><path class="tqwo8s6dw"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-augment-duotone-bold" /></template>
<style>
.aqn8oeb4o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnu2_gbjz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftolpwp2e {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h10");
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

.oq71y_3bz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qypknac_m {
  d: path("M16.5 14h4");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tqwo8s6dw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
