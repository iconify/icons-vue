<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r1p5_ebae"/><path class="eh---ab1x"/><path class="yyyme3b8l"/><path class="syr202grk"/><path class="mr3ctzbkt"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jlpxneb5g"/><path class="h7bcztycq"/><path class="pqrd0wbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:barcode-scan-duotone-thin" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.eh---ab1x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h7bcztycq {
  d: path("M12 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.mr3ctzbkt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

.r1p5_ebae {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.syr202grk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yyyme3b8l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
