<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iiuv-xbvd"/><path class="gjdejs7ie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boolean" /></template>
<style>
.gjdejs7ie {
  d: path("M14 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.iiuv-xbvd {
  d: path("M5.5 6.5h13A3.5 3.5 0 0 1 22 10v4a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 14v-4a3.5 3.5 0 0 1 3.5-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
