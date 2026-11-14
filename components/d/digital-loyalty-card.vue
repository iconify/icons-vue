<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n1art0bgb"/><path class="kdchfjp5f"/><path class="wga6kxsnw"/><path class="kk7jzcbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-loyalty-card" /></template>
<style>
.kdchfjp5f {
  d: path("M7 7.5h10V16H7Z");
}

.kk7jzcbcv {
  d: path("M10 19h4");
}

.n1art0bgb {
  d: path("M5 2.5h14v19H5ZM10.5 5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wga6kxsnw {
  fill: currentColor;
  d: path("m12 9l.735 1.739l1.88.161l-1.426 1.236l.427 1.839L12 13l-1.616.975l.427-1.839L9.385 10.9l1.88-.161Z");
}

</style>
