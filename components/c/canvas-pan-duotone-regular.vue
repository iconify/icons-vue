<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iczafxbjt"/><path class="uobmn7udv"/><path class="y20ytabfw"/><path class="mz9km1btk"/><path class="uihdwhbss"/><path class="brxc3ob5g"/><path class="h2-2dgnfu"/><path class="ae-e09b3w"/><path class="pp54i94hx"/><path class="zrtfv65fm"/><path class="qw0jhccmr"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canvas-pan-duotone-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.brxc3ob5g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 9.5 21 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.iczafxbjt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mz9km1btk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 18.5 12 21l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pp54i94hx {
  d: path("M9.5 5.5 12 3l2.5 2.5");
}

.qw0jhccmr {
  d: path("M5.5 9.5 3 12l2.5 2.5");
}

.uihdwhbss {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 9.5 3 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uobmn7udv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y20ytabfw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 5.5 12 3l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

.zrtfv65fm {
  d: path("M9.5 18.5 12 21l2.5 -2.5");
}

</style>
