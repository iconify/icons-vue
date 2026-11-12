<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="khhypgwbg"/><path class="zn7t-sbpj"/><path class="lc5mm78aw"/><path class="jt0mlr5bg"/><path class="w9lc49y0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:closet-2-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt0mlr5bg {
  d: path("M9 9V13");
}

.khhypgwbg {
  d: path("M19 22V20.5M5 22V20.5");
}

.lc5mm78aw {
  d: path("M15 9V13");
}

.w9lc49y0d {
  d: path("M22 10C22 6.22876 22 4.34315 20.8284 3.17157C19.6569 2 17.7712 2 14 2H10C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10V12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H14C17.7712 20 19.6569 20 20.8284 18.8284C21.7715 17.8853 21.9554 16.4796 21.9913 14");
}

.zn7t-sbpj {
  d: path("M12 20V18M12 14V2");
}

</style>
