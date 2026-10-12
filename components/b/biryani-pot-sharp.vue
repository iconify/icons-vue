<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q0r-77kgr"/><path class="xygj9wb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:biryani-pot-sharp" /></template>
<style>
.q0r-77kgr {
  d: path("M3.75 11.25h16.5v2a8.25 8 0 0 1-16.5 0Zm1.5 0a6.75 4 0 0 1 13.5 0Zm-2.5 0h18.5m-12.5-6c-.9-.75.9-1.5 0-2.5M12 5c-.9-.75.9-1.5 0-2.25m3.25 2.5c-.9-.75.9-1.5 0-2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xygj9wb9v {
  d: path("m5.5 14.25l1.08 1l1.09-1l1.08 1l1.09-1l1.08 1l1.09-1l1.08 1l1.09-1l1.08 1l1.09-1l1.08 1l1.09-1");
}

</style>
