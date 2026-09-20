<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h68oqyb7w"/><path class="yk4p0gbnv"/><path class="wmesk9jct"/><path class="eb8112kbp"/><path class="c7dgfu7wx"/><path class="m46vgkb_g"/><path class="fk1mncnjn"/><path class="xogm81bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backstage-duotone-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.eb8112kbp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 21v-9h4v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fk1mncnjn {
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
}

.h68oqyb7w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m46vgkb_g {
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wmesk9jct {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xogm81bqq {
  d: path("M10 21v-9h4v9");
}

.yk4p0gbnv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
