<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ujsix8bue"/><path class="jsbhw_b4n"/><path class="yg2k73u4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hollow-log" /></template>
<style>
.jsbhw_b4n {
  d: path("M13.5 10.75a4 6 0 1 0 8 0a4 6 0 1 0-8 0Z");
}

.ujsix8bue {
  d: path("M17.5 4.75h-12q-3 0-3 6t3 6h12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yg2k73u4j {
  d: path("M16 10.75a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0ZM2.5 19.5h19");
}

</style>
