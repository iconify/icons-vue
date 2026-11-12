<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="saeh39c6l"/><path class="n7_fvpbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brackets-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7_fvpbed {
  d: path("M9 2.02008C6.20875 2.0839 4.5784 2.35053 3.46447 3.46446C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.5784 21.6495 6.20875 21.9161 9 21.9799");
}

.saeh39c6l {
  d: path("M15 2.02008C17.7913 2.0839 19.4216 2.35053 20.5355 3.46446C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.4216 21.6495 17.7913 21.9161 15 21.9799");
}

</style>
