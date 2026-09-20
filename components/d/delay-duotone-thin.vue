<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wfxvvzbst"/><path class="zgpno7b3v"/><path class="ntt8cbcqj"/><path class="xz6bf05cf"/><path class="gfk0lbm8g"/><path class="l8unaacgj"/><path class="e3aed6d4j"/><path class="pfpu_3ppl"/><path class="wskxlyzso"/><path class="e69i7fcek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delay-duotone-thin" /></template>
<style>
.e3aed6d4j {
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
}

.e69i7fcek {
  d: path("M17 12h5");
}

.gfk0lbm8g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8unaacgj {
  d: path("M2 12h5");
}

.ntt8cbcqj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.wfxvvzbst {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wskxlyzso {
  d: path("M12 12h3");
}

.xz6bf05cf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgpno7b3v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
