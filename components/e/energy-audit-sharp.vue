<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rlrp3u-_r"/><path class="wklko4thw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-audit-sharp" /></template>
<style>
.rlrp3u-_r {
  d: path("M4.25 5.75h15.5v15.5H4.25zm4.75-3h6v3H9z");
}

.wklko4thw {
  d: path("m12.75 9.75l-2.75 4h4L11.25 18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
