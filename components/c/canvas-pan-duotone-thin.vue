<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="fx63l30wc"/><path class="umzu2930r"/><path class="syng65bge"/><path class="ngif51bhj"/><path class="iv5my9b7c"/><path class="h2-2dgnfu"/><path class="ae-e09b3w"/><path class="pp54i94hx"/><path class="zrtfv65fm"/><path class="qw0jhccmr"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canvas-pan-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.fx63l30wc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g6n49udox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iv5my9b7c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 9.5 21 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ngif51bhj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 9.5 3 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pp54i94hx {
  d: path("M9.5 5.5 12 3l2.5 2.5");
}

.qw0jhccmr {
  d: path("M5.5 9.5 3 12l2.5 2.5");
}

.syng65bge {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 18.5 12 21l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.umzu2930r {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
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
