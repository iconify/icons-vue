<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rvz2lnbll"/><path class="kl4f4hnkz"/><path class="nwejmw3ct"/><path class="sgp7fvbwx"/><path class="lr75no4lc"/><path class="keqc2pbxm"/><path class="tuv2qrbve"/><path class="cq9z3jbol"/><path class="l8vricc3a"/><path class="rjbfcabog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idempotency-key-duotone-regular" /></template>
<style>
.cq9z3jbol {
  d: path("M12.5 10v3");
}

.keqc2pbxm {
  d: path("M4 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kl4f4hnkz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 10h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8vricc3a {
  d: path("M17 10h4");
}

.lr75no4lc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwejmw3ct {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 10v3");
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

.sgp7fvbwx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tuv2qrbve {
  d: path("M8 10h7");
}

</style>
