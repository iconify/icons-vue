<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3ry-mu7u"/><path class="pqhroie3c"/><path class="nxauq4bbi"/><path class="bt_2bvgpa"/><path class="t_hkgmbup"/><path class="pbz4y6llk"/><path class="xqz890wro"/><path class="ejtyvbbdg"/><path class="rkhcgsbdl"/><path class="t4vjq-bqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-combo-duotone-thin" /></template>
<style>
.bt_2bvgpa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ejtyvbbdg {
  d: path("M17 15v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxauq4bbi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pbz4y6llk {
  d: path("M5 13v6");
}

.pqhroie3c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3ry-mu7u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.t_hkgmbup {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t4vjq-bqk {
  d: path("m4 9 4 -4 4 4 4 -4 4 4");
}

.xqz890wro {
  d: path("M11 12v7");
}

</style>
