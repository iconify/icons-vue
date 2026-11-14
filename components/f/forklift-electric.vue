<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aogahpb7f"/><path class="ky4f498lt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forklift-electric" /></template>
<style>
.aogahpb7f {
  d: path("M5 9h9v7H5Zm9-5v14m0 0h6.5M5 9V4.5h5m-4 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ky4f498lt {
  d: path("M8.5 10.5L7 13h2.5L8 15.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
