<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="genc22bnp"/><path class="n2tvifbxw"/><path class="xwas84ixu"/><path class="xqlc8_bsl"/><path class="ygsbxnbgt"/><path class="lruok7bvl"/><path class="a61wxkb_y"/><path class="eukpbibyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:closet-linear" /></template>
<style>
.a61wxkb_y {
  d: path("M15 18L17 18");
}

.eukpbibyf {
  d: path("M7 18L9 18");
}

.genc22bnp {
  d: path("M19 22V21.5M5 22V21.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lruok7bvl {
  d: path("M2 15H22");
}

.n2tvifbxw {
  d: path("M12 21V2");
}

.xqlc8_bsl {
  d: path("M10 21H14C17.7712 21 19.6569 21 20.8284 19.8284C22 18.6569 22 16.7712 22 13V10C22 6.22876 22 4.34315 20.8284 3.17157C19.6569 2 17.7712 2 14 2H10C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10V13C2 16.7712 2 18.6569 3.17157 19.8284C4.34315 21 6.22876 21 10 21Z");
}

.xwas84ixu {
  d: path("M15 8V10");
}

.ygsbxnbgt {
  d: path("M2 8H12");
}

</style>
