<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="fllsgz48u"/><path class="l4i0xp9fw"/><path class="x9w5at8kc"/><path class="k5rjwjbvb"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4stwdjmu"/><path class="sok49cc0b"/><path class="hcn7bdzwu"/><path class="v9il_wb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:histogram-quantile-duotone-thin" /></template>
<style>
.fllsgz48u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcn7bdzwu {
  d: path("M15 11v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5rjwjbvb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4i0xp9fw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p4stwdjmu {
  d: path("M7 13v5");
}

.r3faxubne {
  d: path("M4 4v16");
}

.sok49cc0b {
  d: path("M11 8v10");
}

.v9il_wb-q {
  d: path("M6 10h12");
}

.x9w5at8kc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yu-j7jb_g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
