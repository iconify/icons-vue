<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hulgthbyg"/><path class="f0qqebb4d"/><path class="h7t_rfzha"/><path class="ocn0lxb2r"/><path class="rsue96bcd"/><path class="q5jw2tb7h"/><path class="aut8y9hmn"/><path class="gwt34irsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:garden-chair-duotone-bold" /></template>
<style>
.aut8y9hmn {
  d: path("M7 12v7");
}

.f0qqebb4d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 12 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwt34irsi {
  d: path("M15 12v7");
}

.h7t_rfzha {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hulgthbyg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ocn0lxb2r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q5jw2tb7h {
  d: path("m17 12 4 -4");
}

.rsue96bcd {
  d: path("M5 12h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
