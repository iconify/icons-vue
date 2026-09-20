<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="xw83u1b7p"/><path class="asl5t6bkz"/><path class="p8ekm5lyl"/><path class="ocwdg5g_w"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r7dke9bth"/><path class="w8gxvdb9g"/><path class="c2hjexb6t"/><path class="nne1mobhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-bar-stacked-duotone-thin" /></template>
<style>
.asl5t6bkz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c2hjexb6t {
  d: path("M4 14h5");
}

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

.nne1mobhl {
  d: path("M12 14h5");
}

.ocwdg5g_w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p8ekm5lyl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.r7dke9bth {
  d: path("M4 8h7");
}

.w8gxvdb9g {
  d: path("M14 8h5");
}

.xw83u1b7p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
