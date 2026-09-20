<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="ob5udfb7b"/><path class="ufg5si-zr"/><path class="g49gmcc6t"/><path class="dl1qlmu4b"/><path class="k6nj2fbya"/><path class="sixdm4bhp"/><path class="k62k_4bsl"/><path class="n7wfhbrgu"/><path class="cxodqhtoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:log-stream-duotone-thin" /></template>
<style>
.ck7sgubpk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cxodqhtoo {
  d: path("m19 17 2 2 -2 2");
}

.dl1qlmu4b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 17 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g49gmcc6t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k62k_4bsl {
  d: path("M3 13h16");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.n7wfhbrgu {
  d: path("M3 17h11");
}

.ob5udfb7b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sixdm4bhp {
  d: path("M3 9h14");
}

.ufg5si-zr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
