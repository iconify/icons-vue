<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k9jn2o-zp"/><path class="k9on3tb9k"/><path class="vgy66lb4b"/><path class="fvt2-0orr"/><path class="u4sowhi7h"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cold-snap-duotone-bold" /></template>
<style>
.fvt2-0orr {
  d: path("M12 4v8m-4 0 8 -8");
}

.k9jn2o-zp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k9on3tb9k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u4sowhi7h {
  d: path("M4 16h16");
}

.vgy66lb4b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
