<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="haq4atb7e"/><path class="taxmbub4q"/><path class="q26t8cbjw"/><path class="vg9r0qb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:legroom-outline-bold" /></template>
<style>
.haq4atb7e {
  d: path("M6 2v11h12");
}

.q26t8cbjw {
  d: path("M9 17v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.taxmbub4q {
  d: path("M6 17h12");
}

.vg9r0qb2v {
  d: path("M15 17v3");
}

</style>
