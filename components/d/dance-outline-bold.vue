<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="szyef5b0i"/><path class="khevvbcdr"/><path class="g-19mto8o"/><path class="fspoztu7c"/><path class="nzulwvdch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dance-outline-bold" /></template>
<style>
.fspoztu7c {
  d: path("m13 14 -5 5");
}

.g-19mto8o {
  d: path("m9 7 4 4 4 -4");
}

.khevvbcdr {
  d: path("M13 8v6");
}

.nzulwvdch {
  d: path("m13 14 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.szyef5b0i {
  d: path("M10 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
