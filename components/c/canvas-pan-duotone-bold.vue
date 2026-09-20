<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kl0_d31ng"/><path class="v79iaqbup"/><path class="ztc5q2wwb"/><path class="myjkkk6uj"/><path class="jb9_5vb3r"/><path class="f4s6nbboh"/><path class="h2-2dgnfu"/><path class="ae-e09b3w"/><path class="pp54i94hx"/><path class="zrtfv65fm"/><path class="qw0jhccmr"/><path class="zl61012kd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:canvas-pan-duotone-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.f4s6nbboh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 9.5 21 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h2-2dgnfu {
  d: path("M12 3v18");
}

.jb9_5vb3r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 9.5 3 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kl0_d31ng {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.myjkkk6uj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 18.5 12 21l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pp54i94hx {
  d: path("M9.5 5.5 12 3l2.5 2.5");
}

.qw0jhccmr {
  d: path("M5.5 9.5 3 12l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v79iaqbup {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl61012kd {
  d: path("M18.5 9.5 21 12l-2.5 2.5");
}

.zrtfv65fm {
  d: path("M9.5 18.5 12 21l2.5 -2.5");
}

.ztc5q2wwb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 5.5 12 3l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
