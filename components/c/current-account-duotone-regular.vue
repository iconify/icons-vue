<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="wnbj5_30e"/><path class="ldkdjnwcl"/><path class="va0vmebdx"/><path class="mcubrkb2y"/><path class="x1_r36phd"/><path class="ae0h5kb0o"/><path class="x3sflacnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:current-account-duotone-regular" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.k5ecbgu2w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldkdjnwcl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.va0vmebdx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wnbj5_30e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x1_r36phd {
  d: path("M9 12h6");
}

.x3sflacnk {
  d: path("M9 18h6");
}

</style>
