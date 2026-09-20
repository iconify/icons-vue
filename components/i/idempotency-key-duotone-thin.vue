<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rvz2lnbll"/><path class="m69rzacut"/><path class="irguiccla"/><path class="rx5svrbnh"/><path class="l12m2cbki"/><path class="keqc2pbxm"/><path class="tuv2qrbve"/><path class="cq9z3jbol"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idempotency-key-duotone-thin" /></template>
<style>
.cq9z3jbol {
  d: path("M12.5 10v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irguiccla {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l12m2cbki {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8vricc3a {
  d: path("M17 10h4");
}

.m69rzacut {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rjbfcabog {
  d: path("M17 16h4");
}

.rvz2lnbll {
  fill: currentColor;
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rx5svrbnh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tuv2qrbve {
  d: path("M8 10h7");
}

</style>
