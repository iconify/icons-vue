<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e9lwpbb-y"/><path class="v_qmwzbgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cpu-throttle" /></template>
<style>
.e9lwpbb-y {
  d: path("M11.8 15H5V5h10v6.3M8.5 2.5V5m3-2.5V5m-3 10v2.5m3-2.5v2.5m-9-9H5m-2.5 3H5m10-3h2.5m-1.3 3h1.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_qmwzbgd {
  d: path("M8 8h4v4H8Zm7.5 6.75l3 3l3-3m-6 3.75l3 3l3-3");
}

</style>
