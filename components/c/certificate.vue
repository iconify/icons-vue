<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wvrqgpbdv"/><path class="avkhpibhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certificate" /></template>
<style>
.avkhpibhk {
  d: path("M13 10.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm1.25 2.5l-.75 7.25m3.75-7.25L18 20.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvrqgpbdv {
  d: path("M2.5 4h19v13.5h-19ZM6 8.5h5M6 12h3.5");
}

</style>
