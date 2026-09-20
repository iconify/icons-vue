<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="fx63l30wc"/><path class="bt_2bvgpa"/><path class="tdsnubcpt"/><path class="rs3fs1bee"/><path class="k6nj2fbya"/><path class="ae-e09b3w"/><path class="rkhcgsbdl"/><path class="zbpm1d36f"/><path class="hrjweb57d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cname-record-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.bt_2bvgpa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fx63l30wc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrjweb57d {
  d: path("m9 15 3 -3 3 3");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.rs3fs1bee {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tdsnubcpt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zbpm1d36f {
  d: path("m9 8 3 -3 3 3");
}

</style>
