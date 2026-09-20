<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kj8xpdbcm"/><path class="no2al_bwc"/><path class="qeiyu6bjx"/><path class="ql_xiaczr"/><path class="gmcwnnbyg"/><path class="o7xcj9b5m"/><path class="iu3j18b-o"/><path class="izkbhz86a"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:extractor-duotone-regular" /></template>
<style>
.cfyvl-o0i {
  d: path("M16 12h4");
}

.gmcwnnbyg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iu3j18b-o {
  d: path("M9 8h4");
}

.izkbhz86a {
  d: path("M9 12h4");
}

.kj8xpdbcm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 2H6v19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.no2al_bwc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7xcj9b5m {
  d: path("M13 2H6v19h8");
}

.qeiyu6bjx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ql_xiaczr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
