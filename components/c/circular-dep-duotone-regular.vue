<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u2zpw1b_q"/><path class="wjrlmwbln"/><path class="b19alrbis"/><path class="mqpo1mbpl"/><path class="gv5xmqiem"/><path class="qck_wensm"/><path class="wzx0dxb2r"/><path class="nuc2dr9ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:circular-dep-duotone-regular" /></template>
<style>
.b19alrbis {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 2 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gv5xmqiem {
  d: path("M14.39 5.42a7 7 0 0 1 0 13.16");
}

.mqpo1mbpl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 16 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuc2dr9ql {
  d: path("m12 16 -3 3 3 3");
}

.qck_wensm {
  d: path("M9.61 18.58a7 7 0 0 1 0 -13.16");
}

.u2zpw1b_q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.39 5.42a7 7 0 0 1 0 13.16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wjrlmwbln {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.61 18.58a7 7 0 0 1 0 -13.16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wzx0dxb2r {
  d: path("m12 2 3 3 -3 3");
}

</style>
