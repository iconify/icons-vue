<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lzbpucbiv"/><path class="eg2u_0b1d"/><path class="r6xbnkbzi"/><path class="vw-f69bhv"/><path class="zoewprblb"/><path class="ojq3d2bwe"/><path class="v28q9db1j"/><path class="hbuw0obat"/><path class="r7pmyrb1c"/><path class="vcbx2ik3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jailbreak-duotone-bold" /></template>
<style>
.eg2u_0b1d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hbuw0obat {
  d: path("M17 3v6");
}

.lzbpucbiv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ojq3d2bwe {
  d: path("M5 3v18");
}

.r6xbnkbzi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r7pmyrb1c {
  d: path("M14 15h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v28q9db1j {
  d: path("M11 3v18");
}

.vcbx2ik3k {
  d: path("m17 12 3 3 -3 3");
}

.vw-f69bhv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zoewprblb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 12 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
