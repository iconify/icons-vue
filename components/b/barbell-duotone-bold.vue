<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jb_v2ub8s"/><path class="mmx2_7bmn"/><path class="q80kgo3im"/><path class="eovexh4sc"/><path class="v0da073eq"/><path class="vslz5yb3q"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gfdpeof0d"/><path class="y_uork5-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:barbell-duotone-bold" /></template>
<style>
.eovexh4sc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gfdpeof0d {
  d: path("M9 7v10");
}

.jb_v2ub8s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mmx2_7bmn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.q80kgo3im {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

.v0da073eq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.y_uork5-p {
  d: path("M15 7v10");
}

</style>
