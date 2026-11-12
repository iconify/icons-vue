<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ykueg1b1u"/><path class="nr7t2bb1e"/><path class="p4bgj8o4w"/><path class="ck1800buq"/><path class="si_mtzbvj"/><path class="l6e0kx4od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-text-broken" /></template>
<style>
.ck1800buq {
  d: path("M6.5 17.5H12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6e0kx4od {
  d: path("M21.9447 8H2.05469");
}

.nr7t2bb1e {
  d: path("M13.5 8L17 2.5");
}

.p4bgj8o4w {
  d: path("M6.5 14H14.5");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.ykueg1b1u {
  d: path("M7 8L10.5 2.5");
}

</style>
