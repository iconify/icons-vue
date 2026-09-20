<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="o0lh1k1dl"/><path class="lwp9rob3c"/><path class="x_r014yat"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jlfjgzbqx"/><path class="dl7inkt3h"/><path class="ae0h5kb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:format-check-duotone-thin" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.dl7inkt3h {
  d: path("M10.5 12H15");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.lwp9rob3c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12H15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o0lh1k1dl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x_r014yat {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
