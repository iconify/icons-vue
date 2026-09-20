<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdjnqqbyj"/><path class="cl77g6gmt"/><path class="sb_ge0zjk"/><path class="xhoq0u93m"/><path class="c7dgfu7wx"/><path class="m46vgkb_g"/><path class="fk1mncnjn"/><path class="xogm81bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backstage-duotone-regular" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.cl77g6gmt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fk1mncnjn {
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
}

.m46vgkb_g {
  d: path("M3 4v17h2.5C7 21 7 20 7 18V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sb_ge0zjk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 4v17h-2.5C17 21 17 20 17 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vdjnqqbyj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhoq0u93m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 21v-9h4v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xogm81bqq {
  d: path("M10 21v-9h4v9");
}

</style>
