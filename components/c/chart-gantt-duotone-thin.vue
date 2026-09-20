<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="hunp6e5io"/><path class="jb3sa9bbh"/><path class="ud091vbff"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r_r678bum"/><path class="lqiw_3bos"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gantt-duotone-thin" /></template>
<style>
.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hunp6e5io {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jb3sa9bbh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqiw_3bos {
  d: path("M10 12h7");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r_r678bum {
  d: path("M6 7h6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ud091vbff {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
