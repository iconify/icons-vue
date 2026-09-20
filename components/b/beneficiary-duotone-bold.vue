<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z1ra8bb5p"/><path class="vspm3ybjo"/><path class="qcxa0jb0g"/><path class="f-glw__bg"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="u7m7z6ojw"/><path class="wuk2mlziz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beneficiary-duotone-bold" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.f-glw__bg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qcxa0jb0g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u7m7z6ojw {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vspm3ybjo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wuk2mlziz {
  d: path("M7 19h10");
}

.z1ra8bb5p {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

</style>
