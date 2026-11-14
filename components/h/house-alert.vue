<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="chkh74bjc"/><path class="tl13t1q5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-alert" /></template>
<style>
.chkh74bjc {
  d: path("M15.16 20H4v-9.5l8-7l8 7v1.44");
}

.tl13t1q5l {
  d: path("M9.5 20v-4a2.5 2.5 0 0 1 5 0v4m3.5-5.25v3.5M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
