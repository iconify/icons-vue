<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ckt-nxbxw"/><path class="vgy66lb4b"/><path class="s15_3u2gx"/><path class="xe85kccyz"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="bdxedv3gx"/><path class="i4nkkkbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exam-timer-duotone-bold" /></template>
<style>
.bdxedv3gx {
  d: path("M6 3v3l6 6 6 -6V3");
}

.ckt-nxbxw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i4nkkkbsh {
  d: path("M6 21v-3l6 -6 6 6v3");
}

.rjrs_5bsc {
  d: path("M6 3h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s15_3u2gx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v3l6 6 6 -6V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vgy66lb4b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xe85kccyz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21v-3l6 -6 6 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
