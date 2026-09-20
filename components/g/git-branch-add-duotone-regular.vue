<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6an06b6t"/><path class="h03wmtogt"/><path class="wras9db_y"/><path class="j8k_iqpva"/><path class="re0h2d5md"/><path class="tt7ypiikb"/><path class="zgod0v2rr"/><path class="du3agkbjb"/><path class="objyy5b5b"/><path class="r2dk7difb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-branch-add-duotone-regular" /></template>
<style>
.du3agkbjb {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h03wmtogt {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j8k_iqpva {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.objyy5b5b {
  d: path("M17 9v6");
}

.p6an06b6t {
  fill: currentColor;
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r2dk7difb {
  d: path("M14 12h6");
}

.re0h2d5md {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tt7ypiikb {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wras9db_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgod0v2rr {
  d: path("M7 8.5v7");
}

</style>
