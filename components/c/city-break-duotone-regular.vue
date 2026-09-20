<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d73fpzqiz"/><path class="y0exnbbbd"/><path class="qxo13ebua"/><path class="mfdaze0wn"/><path class="lbkuffism"/><path class="n36352b2b"/><path class="j3g0obcgt"/><path class="m_ifpmwzr"/><path class="w-c31ggft"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:city-break-duotone-regular" /></template>
<style>
.d73fpzqiz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21V8h6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j3g0obcgt {
  d: path("M13 21V4h6v17");
}

.lbkuffism {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m_ifpmwzr {
  d: path("M4 12h6");
}

.mfdaze0wn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n36352b2b {
  d: path("M4 21V8h6v13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.qxo13ebua {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-c31ggft {
  d: path("M13 9h6");
}

.y0exnbbbd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 21V4h6v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
