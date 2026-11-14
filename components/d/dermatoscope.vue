<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zremgbobi"/><path class="vt0mkkbui"/><path class="fsc3ttbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dermatoscope" /></template>
<style>
.fsc3ttbcq {
  fill: currentColor;
  d: path("M8.25 9.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vt0mkkbui {
  d: path("M5.5 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.zremgbobi {
  d: path("M3 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm10.184 6.159l2.475-2.475l5.657 5.657l-2.475 2.475Z");
}

</style>
