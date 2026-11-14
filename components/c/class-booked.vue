<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr8m1_bim"/><path class="loqzp35xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:class-booked" /></template>
<style>
.fr8m1_bim {
  d: path("M3 4.5h18V21H3Zm0 5h18m-13-7v4m8-4v4");
}

.loqzp35xo {
  d: path("m8 15l3 3l5.5-5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
