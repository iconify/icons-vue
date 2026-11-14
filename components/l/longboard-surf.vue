<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="am-8_fjjp"/><path class="aiucu5zzp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:longboard-surf" /></template>
<style>
.aiucu5zzp {
  d: path("M7.75 18L11 20.5l-1.25-3.75");
}

.am-8_fjjp {
  d: path("M4 19c0-5.5 9.5-15 15-15c0 5.5-9.5 15-15 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
