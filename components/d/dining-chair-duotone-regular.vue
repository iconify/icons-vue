<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iozu5mbsj"/><path class="bb8-_jxhl"/><path class="t1wu4l4cb"/><path class="jvbt2hbkc"/><path class="bli2u1bne"/><path class="ckxsheb0b"/><path class="z22xlf92i"/><path class="u3jess8hd"/><path class="o682nlgep"/><path class="r182r524c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dining-chair-duotone-regular" /></template>
<style>
.bb8-_jxhl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bli2u1bne {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ckxsheb0b {
  d: path("M7 3v10h10V3");
}

.iozu5mbsj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3v10h10V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvbt2hbkc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o682nlgep {
  d: path("M17 16v5");
}

.r182r524c {
  d: path("M7 9h10");
}

.t1wu4l4cb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u3jess8hd {
  d: path("M7 16v5");
}

.z22xlf92i {
  d: path("M5 16h14");
}

</style>
