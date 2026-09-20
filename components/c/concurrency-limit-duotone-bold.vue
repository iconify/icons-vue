<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q6ohrfbvx"/><path class="k0l21tbkp"/><path class="awzyt9bop"/><path class="jgq8ape0r"/><path class="z5jtjknvm"/><path class="bj2hlhbfp"/><path class="w03o55b0h"/><path class="ds_qvubnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:concurrency-limit-duotone-bold" /></template>
<style>
.awzyt9bop {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bj2hlhbfp {
  d: path("M3 12h12");
}

.ds_qvubnl {
  d: path("M19 3v18");
}

.jgq8ape0r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k0l21tbkp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6ohrfbvx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w03o55b0h {
  d: path("M3 19h12");
}

.z5jtjknvm {
  d: path("M3 5h12");
}

</style>
