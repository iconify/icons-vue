<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w-h7h0dho"/><path class="v0da073eq"/><path class="skx5w-b_a"/><path class="oy0_t5b-m"/><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:knowledge-cutoff-duotone-bold" /></template>
<style>
.g-pndgz7k {
  d: path("M2 12h10");
}

.me2guebva {
  d: path("m18 9.5 3 3");
}

.oy0_t5b-m {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pkr04599e {
  d: path("m21 9.5 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skx5w-b_a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v0da073eq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-h7h0dho {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_uork5-p {
  d: path("M15 7v10");
}

</style>
