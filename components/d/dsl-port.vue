<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xmy0-ibxc"/><path class="t016zfhbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dsl-port" /></template>
<style>
.t016zfhbs {
  d: path("M7 6.5h10v4H7ZM9.5 14h5v3.5h-5Zm2.5 3.5V19a2.5 2.5 0 0 0 2.5 2.5H19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmy0-ibxc {
  d: path("M2.5 3h19v11h-19Z");
}

</style>
