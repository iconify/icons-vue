<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuroep7vz"/><path class="lo3ih2b5e"/><path class="hsfhm_bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-type-switch" /></template>
<style>
.hsfhm_bqu {
  d: path("M14.5 16H21m-1.75-1.75L21 16l-1.75 1.75M21.5 20H15m1.75-1.75L15 20l1.75 1.75");
}

.lo3ih2b5e {
  fill: currentColor;
  d: path("M5.5 20.5V11H8v9.5Zm5.75-.3v.3h-1.5V5h1.5v14.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuroep7vz {
  d: path("M3.5 3v17.5h8.1");
}

</style>
