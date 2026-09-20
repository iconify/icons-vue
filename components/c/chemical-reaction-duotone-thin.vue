<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mt0ldub2a"/><path class="gwbufwb5t"/><path class="cyjrdve-j"/><path class="fgvm0wbox"/><path class="r2uy21bnv"/><path class="wa9xnbbwt"/><path class="rzt8fd71i"/><path class="vezq7pbcc"/><path class="ymhuvfz3p"/><path class="hxtix3e9b"/><path class="y0y0ccsoe"/><path class="cxgftibra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chemical-reaction-duotone-thin" /></template>
<style>
.cxgftibra {
  d: path("m12 10 2 2 -2 2");
}

.cyjrdve-j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fgvm0wbox {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwbufwb5t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6v11h6V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxtix3e9b {
  d: path("M15 6v11h6V6");
}

.mt0ldub2a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r2uy21bnv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzt8fd71i {
  d: path("M2 6h8");
}

.vezq7pbcc {
  d: path("M3 6v11h6V6");
}

.wa9xnbbwt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y0y0ccsoe {
  d: path("M10 12h4");
}

.ymhuvfz3p {
  d: path("M14 6h8");
}

</style>
