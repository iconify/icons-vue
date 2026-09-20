<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="wo2zl_ynb"/><path class="gewz4pcru"/><path class="u0eeppbtm"/><path class="q7zfvpbhn"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4stwdjmu"/><path class="sok49cc0b"/><path class="hcn7bdzwu"/><path class="v9il_wb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:histogram-quantile-duotone-bold" /></template>
<style>
.dh-nlhghu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gewz4pcru {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hcn7bdzwu {
  d: path("M15 11v7");
}

.jiw8u-asa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p4stwdjmu {
  d: path("M7 13v5");
}

.q7zfvpbhn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sok49cc0b {
  d: path("M11 8v10");
}

.u0eeppbtm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9il_wb-q {
  d: path("M6 10h12");
}

.wo2zl_ynb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
