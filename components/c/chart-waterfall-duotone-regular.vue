<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iexemb3jd"/><path class="ynw_yiymv"/><path class="fyju44b5a"/><path class="vh59wqa6i"/><path class="nt8ufs66i"/><path class="ig8k5lhpw"/><path class="hlt9oudyd"/><path class="goqqd75_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-waterfall-duotone-regular" /></template>
<style>
.fyju44b5a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.goqqd75_r {
  d: path("M20 4v5");
}

.hlt9oudyd {
  d: path("M15 9v7");
}

.iexemb3jd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 6v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ig8k5lhpw {
  d: path("M10 11v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nt8ufs66i {
  d: path("M5 6v5");
}

.vh59wqa6i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynw_yiymv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
