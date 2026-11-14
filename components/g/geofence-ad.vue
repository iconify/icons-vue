<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qjntmcb7n"/><path class="g67-i-b4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geofence-ad" /></template>
<style>
.g67-i-b4a {
  d: path("M10.5 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.qjntmcb7n {
  d: path("M14.459 2.824a9.5 9.5 0 0 1 6.717 6.717m0 4.918a9.5 9.5 0 0 1-6.717 6.717m-4.918 0a9.5 9.5 0 0 1-6.717-6.717m0-4.918a9.5 9.5 0 0 1 6.717-6.717M12 17.5c-2.5-2.5-4-4.5-4-7a4 4 0 0 1 8 0c0 2.5-1.5 4.5-4 7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
