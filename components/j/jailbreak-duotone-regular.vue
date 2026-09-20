<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vn749yfck"/><path class="y49dugb1c"/><path class="zuz5mbbiq"/><path class="b543nccbg"/><path class="ec357i62x"/><path class="ojq3d2bwe"/><path class="v28q9db1j"/><path class="hbuw0obat"/><path class="r7pmyrb1c"/><path class="vcbx2ik3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jailbreak-duotone-regular" /></template>
<style>
.b543nccbg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ec357i62x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hbuw0obat {
  d: path("M17 3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ojq3d2bwe {
  d: path("M5 3v18");
}

.r7pmyrb1c {
  d: path("M14 15h5");
}

.v28q9db1j {
  d: path("M11 3v18");
}

.vcbx2ik3k {
  d: path("m17 12 3 3 -3 3");
}

.vn749yfck {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y49dugb1c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuz5mbbiq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
